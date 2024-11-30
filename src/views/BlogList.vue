<template>
    <div>
        <h1>Blog List</h1>
        <ul>
            <li><router-link :to="'/blog/1'">Blog Post 1</router-link></li>
            <li><router-link :to="'/blog/2'">Blog Post 2</router-link></li>
        </ul>
    </div>
</template>