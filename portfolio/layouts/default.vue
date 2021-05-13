<!-- First off I created my vue project using "npm install -g @vue/cli-init"
2. created a nuxtjs project "vue init  nuxt/vue portfolio"; // template was created
3. cd into it and install my required modules using "npm install"; //modules were install
4.then moved to editing the default template
i. started by adding bumal css and googlefonts to my nuxt.config.js "head; link[] tag"
ii. then we moved to the layouts folder since we dont want to do alot of working creating new folders and stuff again
iii. we then went to default.vue  and deleted the codes and we have this,
iv. moved to "components folder" and created the Navbar.vue file and you have that
v. i imported the Navbar.vue into default.vue in the <<script>
import Navbar from '../components/Navbar'

export default ({
 Navbar
})
</script>

vi. moved to pages folder to start creating the pages

-->


<template>
  <div>
    <navbar></navbar>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar'

export default {
  components: { Navbar },
  
}
</script>

<style>
html {
  font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
}
</style>

