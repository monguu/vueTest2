<template>
  <div>
    <h1>{{ title }}</h1>
    <slot name="header" :kwongu="kwongu"></slot>
    <div>{{ name }}</div>
    <slot></slot>
    <button @click="updatename">눌러봐</button>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: false,
      default: "default",
    },
    name: {
      type: String,
      required: false,
      default: "default name",
    },
  },
  data() {
    return {
      kwongu: "coding!!!!",
      // name: 'kwongu hi! ',
    };
  },
  methods: {
    updatename() {
      this.name = "나는 권구가 아니다 !";
    },
  },
};
</script>

<style scoped>
</style>