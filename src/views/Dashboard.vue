<template>
    <div>
        <h1>Dashboard</h1>
        <p>This is a protected route.</p>
        <button @click="logout">Đăng xuất</button>
    </div>
</template>

<script>
export default {
    methods: {
        logout() {
            localStorage.setItem('isAuthenticated', false);
            this.$router.push({ name: 'Home' });
        }
    }
}
</script>