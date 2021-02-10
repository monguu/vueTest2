<template>
  <div>
    
    <h1>
      Kwongu Kim,Coding
    </h1>
    <KwonguCoding title="home title" name="kwongu name"/>
  </div>
  
</template>


<script>
import KwonguCoding from '@/components/kwongucoding.vue'
export default {
  components: {
    KwonguCoding,
},
  data() {
    return{
      name: 'kwongu'
    }
  }
}
</script>

<style scoped>
h1 {
  color: rgb(13, 33, 122);
}
p {
  font-size: 30px;
  color: salmon
  
}

</style>