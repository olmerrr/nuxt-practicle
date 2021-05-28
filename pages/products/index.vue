<template>
  <section>
    <h1>This is Products page</h1>
    <button @click="goToProductOne">Go to product-1</button>
    <button @click="goToProductTwo">Go to product-2</button>
  </section>
</template>
<script>

export default {
  methods: {
    goToProductOne() {
        this.$router.push('/products/1')
    },
    goToProductTwo() {
        this.$router.push('/products/2')

    }
  }
}
</script>
