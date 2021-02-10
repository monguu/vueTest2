<template>
  <div class="about">
    <div>
      <KwonguCoding>
        <template #header="{ kwongu }">
          <p>header1 {{ kwongu }}</p>
        </template>
        <!-- v-=slot  ====> #  축약 -->
        <template #default>
          <p>body1</p>
        </template>
      </KwonguCoding>
    </div>
  </div>
</template>

<script>
import KwonguCoding from "@/components/kwongucoding";
export default {
  components: {
    KwonguCoding,
  },
  data() {
    return {
      // title: 5,
    };
  },
};
</script>