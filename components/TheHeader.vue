<template>
        <header class="header">
          <nav class="nav">
            <router-link to="/" class="nav-link" exact-active-class="active-link">Home</router-link>
            <router-link to="/users" class="nav-link" exact-active-class="active-link">Users</router-link>
            <router-link to="/products" class="nav-link" exact-active-class="active-link">Products</router-link>
          </nav>
        </header>
</template>

<style scoped>
  .header {
    padding: 30px 20px;
    display: flex;
    justify-content: space-between;
    background-color: #333;
  }  
  
  .nav-link {
    color:#fff;
    margin-right: 16px;
    font-size: 18px;
    font-weight: 500;
    text-decoration: none;
  }

   .active-link{
    color: red;
  }

</style>