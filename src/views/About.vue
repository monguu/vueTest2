<template>
  <div class="about">
    <h1>This is an about page</h1>
    <KwonguCoding />
  </div>
</template>

<script>
import KwonguCoding from '@/components/kwongucoding'
export default {
  components: {
    KwonguCoding,
  },
  data () {
    return {
      title: 5
    }
  }
  
}
</script>