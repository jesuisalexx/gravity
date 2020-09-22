<template>
    <div>
         <div class="header">
           <div class="logo">Gravity</div>
           <img class="zoom" src="../assets/icons/zoom.svg" alt="">
           <img class="menu" src="../assets/icons/menu.svg">
         </div>
    </div>
</template>

<script>
export default {
  name: 'HomePgHeader',
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  height: 150px;
  width: 80%;
  margin-left: 10%;
  margin-right: 10%;
  align-items: center;
}
.logo {
  font-family: 'Roboto', sans-serif;
  font-weight: bold;
  font-size: 27px;
}
</style>
