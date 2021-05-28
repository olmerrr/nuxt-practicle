<template>
  <section class="users-wrap">
    <h1>Users</h1>
    <input type="text" placeholder="Name " v-model="userId" />
    <button @click="addUser">Add User</button>
  </section>
</template>

<script>

export default {
  layout: 'users',
  data() {
    return {
      userId: ''
    }
  },
  methods: {
    addUser() {
      this.$router.push('/users/' + this.userId)
    }
  }
}
</script>
<style scoped>
  .users-wrap {
    padding: 10px;
  }
</style>