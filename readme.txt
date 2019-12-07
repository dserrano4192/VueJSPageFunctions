Intro: Vue.js VSwitch

A tutorial on a simple and easy way to transition to other pages using Vue functions instead of Vue Router.


Why Use This Instead of Vue Router?

It depends on the application you are building. Some applications have different requirements. If a website is highly devoted to SEO you may want to consider using some Vue Router elements because this method favors a website with smaller number of URLs. Google loves URLs so Vue Router would be more efficient for a website with a large number of URLs involved. This method suits simple websites best and I prefer it over the Vue Router method because it's much simpler and for a website with few URLs it is not as important to focus on navigation bar links and instead focus on main page content and meta tags when doing SEO. Vue.js router is necessary for learning to route to pages on the internet and assigning URLs. This method is the standard method of creating separate pages for Vue.js components. However, it is not the only method and here's one I developed myself.


Main Benefits

Quick, Easy and Simple, No NPM Installs required, Works Every Time


How It Works

Using Vue.js we can specify a Vue.js Click Function that enables a callback function on click. The callback can be anything we want bue we will use a function that specifies whether or not to show an object. This is done by using a 'v-if' function that references a data object. That data object is then turned on or off by the user clicking on the link because that click function references a function that alters the data object to show or hide a component from the Vue.js App.


You will need node.js available here: https://nodejs.org/en/

And...

You will also need this: https://vuejs.org/

To complete this...

Once you install node.js and Vue.js onto node.js you can use the VSwitch.

Note: You need to know JavaScript and Linux to understand how to work with node.js and Vue.js.

