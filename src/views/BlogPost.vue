<template>
    <div>
        <h1>Blog Post {{ $route.params.id }}</h1>
        <p>This is the content of blog post {{ $route.params.id }}.</p>
        <router-link to="/blog">Back to Blog List</router-link>
    </div>
</template>