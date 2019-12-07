<template>
    <div>
        <h1>Contact Me for More Information</h1>
        <p class="border"></p>
        <h3>Email Address</h3>
        <p style="margin-bottom: 50px;">dserrano4192@gmail.com</p>
        <p class="border" style="width: 200px;"></p>
        <button onclick="window.open('https://www.ninjawebsitedesign.com/','popUpWindow')">Ninja Web Design | My Website</button>
    </div>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style lang="less" scoped>
button{
    background: rgb(32,32,32);
    color: white;
    font-weight: bolder;
    padding: 20px;
    padding-right: 10px;
    padding-left: 10px;
    cursor: pointer;
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