<template>
  <section>
    <h2>This prod {{ $route.params.id }}</h2>
    <button click="$route.push('/products/')">go to Product page</button>
  </section>
</template>