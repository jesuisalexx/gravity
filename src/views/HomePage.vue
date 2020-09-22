<template>
   <div class="main">
     <HomePgHeader />
     <HomePgMain />
   </div>
</template>
<script>

import HomePgHeader from '@/views/HomePgHeader.vue';
import HomePgMain from '@/views/HomePgMain.vue';

export default {
  name: 'HomePage',
  components: { HomePgHeader, HomePgMain },
};
</script>

<style scoped>
.main {
  height: 885px;
  width: 100%;
  background: #F4F4F4;
}
</style>
