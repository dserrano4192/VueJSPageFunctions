<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>Vue.js VSwitch</h1>
    <p class="border"></p>
    <p>
      A tutorial on a simple and easy way to transition to other pages using Vue functions instead of Vue Router.
    </p>
    <h2>Why Use This Instead of Vue Router?</h2>
    <p class="border" style="width: 200px;"></p>
    <p>It depends on the application you are building. Some applications have different requirements. If a website is highly devoted to SEO you may want to consider using some Vue Router elements because this method favors a website with smaller number of URLs. Google loves URLs so Vue Router would be more efficient for a website with a large number of URLs involved. This method suits simple websites best and I prefer it over the Vue Router method because it's much simpler and for a website with few URLs it is not as important to focus on navigation bar links and instead focus on main page content and meta tags when doing SEO. Vue.js router is necessary for learning to route to pages on the internet and assigning URLs. This method is the standard method of creating separate pages for Vue.js components. However, it is not the only method and here's one I developed myself.</p>
    <h2>Main Benefits</h2>
    <ul>
      <li>Quick, Easy and Simple</li>
      <li>No NPM Installs required</li>
      <li>Works Every Time</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: white;
  text-decoration: underline;
  font-style: italic;
}
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
ul{
  font-weight: bolder;
}
li{
  text-decoration: underline;
  font-style: italic;
}
</style>
