<template>
    <div>
        <h1>User Profile</h1>
        <nav>
            <router-link to="info">Info</router-link> |
            <router-link to="settings">Settings</router-link>
        </nav>
        <router-view></router-view>
    </div>
</template>