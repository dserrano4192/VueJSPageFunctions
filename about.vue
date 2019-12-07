<template>
    <div>
        <h1>About The Vue.js VSwitch</h1>
        <p>Using Vue.js we can specify a Vue.js Click Function that enables a callback function on click. The callback can be anything we want bue we will use a function that specifies whether or not to show an object. This is done by using a 'v-if' function that references a data object. That data object is then turned on or off by the user clicking on the link because that click function references a function that alters the data object to show or hide a component from the Vue.js App.</p>
    </div>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style lang="css" scoped>
p{
  background: rgb(32,32,32);
  padding: 20px;
  width: 80%;
  margin: auto;
  text-align: center;
  color: rgb(230,230,230);
  line-height: 1.5;
  font-weight: bolder;
}
.border{
  border-top: thin solid black;
  width: 300px;
  height: 2px;
  margin: auto;
  margin-bottom: 20px;
}
p.border{
  padding: 0;
}
</style>
