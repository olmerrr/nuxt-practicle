<template>
  <h2>Single user, with ID: {{ $route.params.id }}</h2>
</template>
<script>
export default {
  validate(data) {
    return data.params.id == 1;
  },
};
</script>