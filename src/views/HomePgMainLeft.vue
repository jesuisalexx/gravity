<template>
  <div class="basic">
    <div class="text-block">
      <div class="title">Work around you <br>  and your team</div>
      <div class="description">From ads that dance or sing to MTV-like commercials,<br> online
        advertisers are now using a new type of <br> technology “rich media” to attract consumers.
      </div>
      <button class="btn">get started</button>
      <div class="bottom">
          <div class="one">01</div>
          <div class="dark"></div>
          <div class="light"></div>
          <div class="three">03</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePgMainLeft',
};
</script>

<style scoped>
.basic{
  width: 50%;
}
.text-block {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.title {
  font-family: 'Fira Sans', sans-serif;
  font-size: 60px;
  font-weight: bold;
  padding-top: 70px;
}
.description {
  margin-top: 50px;
  font-family: 'Fira Sans', sans-serif;
  font-size: 18px;
  opacity: 70%;
}
.btn {
  margin-top: 50px;
  width: 189px;
  height: 50px;
  background: #4737FF;
  color: white;
  border: none;
  outline: none;
  text-transform: uppercase;
}
.bottom {
  margin-top: 120px;
  display: flex;
  width: 346px;
  height: 18px;
  font-family: 'Fira Sans', sans-serif;
  align-items: center;
  font-weight: bold;
}
.one {
  height: 18px;
  width: 21px;
  margin-right: 15px;
}
.dark {
  width: 139px;
  height: 2px;
  background: #C6B393;
}
.light {
  width: 139px;
  height: 2px;
  background: #D7D4D4;
}
.three {
  margin-left: 15px;
}
</style>
