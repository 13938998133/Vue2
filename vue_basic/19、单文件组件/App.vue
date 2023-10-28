<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
import School from "./School.vue";
import Student from "./Student.vue";

export default {
  //引入组件
  name: "App",
  components: {
    School,
    Student,
  },
};
</script>

<style>
</style>