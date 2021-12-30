<template>
  <li>
    <h2><strong>Name:</strong>{{ name }}</h2>
    <h3><strong>Age:</strong>{{ age }}</h3>
  </li>
</template>

<script>
export default {
  props: {
    id: String,
    name: String,
    age: String,
  },
};
</script>