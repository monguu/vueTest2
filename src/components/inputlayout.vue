 <template>
  <div>
    <label for="">Name</label>
    <input
      type="text"
      :value="value"
      style="padding: 10px; border: 2px solid red"
      @input="$emit('input', $event.target.value)"
    />
    <br /><button style="margin-top: 10px">Submit</button>
  </div>
</template>

<script>
export default {
  props: {
    value: {
      type: String,
      required: false,
      default: "default",
    },
  },
  //   methods: {
  //     updateName(e) {
  //       console.log(e.target.value);
  //       this.$emit("npdate-name", e.target.value);
  //     },
  //   },
};
</script>

<style scoped>
</style> 