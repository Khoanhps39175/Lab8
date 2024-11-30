<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/blog">Blog List</router-link></li>
          <li><router-link to="/profile">User Profile</router-link></li>
          <li><router-link to="/dashboard">Dashboard</router-link></li>
          <li><router-link to="/login">Login</router-link></li>
        </ul>
      </nav>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
/* Add some basic styles */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}

header {
  background: #42b983;
  padding: 10px;
}

header nav ul {
  list-style-type: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 20px;
}

header nav ul li {
  display: inline;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

header nav ul li a.router-link-active {
  text-decoration: underline;
}

main {
  margin: 20px;
}
</style>
