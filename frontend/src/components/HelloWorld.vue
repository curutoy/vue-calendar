<template>
  <div>
    <div v-if="visiblity">
      <p>visiblity: true</p>
      <p>{{ message }}</p>
    </div>
    <div v-else>
      <p>visiblity: false</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: () => ({
    message: "Hello World",
    visiblity: true,
  }),
};
</script>
