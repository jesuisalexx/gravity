<template>
  <div>
     <div class="main">
        <HomePgMainLeft />
        <HomePgMainRight />
     </div>
  </div>
</template>

<script>
import HomePgMainLeft from '@/views/HomePgMainLeft.vue';
import HomePgMainRight from '@/views/HomePgMainRight.vue';

export default {
  name: 'HomePgMain',
  components: { HomePgMainRight, HomePgMainLeft },
};
</script>

<style scoped>
.main {
  display: flex;
  margin-left: 10%;
  height: 800px;
  width: 90%;
}
</style>
