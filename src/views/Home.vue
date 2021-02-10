<template>
  <div>
    <h1>Kwongu Kim,Coding</h1>
    <form action="">
      <InputLayout v-model="name" />
      <br /><button style="margin-top: 10px">Submit</button>
    </form>
    {{ name }}
  </div>
</template>


<script>
import InputLayout from "@/components/inputlayout.vue";
export default {
  components: { InputLayout },
  data() {
    return {
      name: "",
    };
  },

  beforeCreate() {},
  created() {},
  beforeMount() {},
  mounted() {
    //DOM
  },
  beforeUpdate() {},
  updated() {},
  beforeDestroy() {
    // event close
  },
  destroyed() {},

  // methods: {
  //   updateName(name) {
  //     this.name = name;
  //   },
  // },
};
</script>

<style scoped>
h1 {
  color: rgb(13, 33, 122);
}
p {
  font-size: 30px;
  color: salmon;
}
</style>