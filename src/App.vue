<template>
  <div id="app">
    <HeaderPage />
    <BlogContent />
    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue'
import BlogContent from './components/BlogContent.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    FooterPage,
    BlogContent
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Jost:ital@0;1&display=swap');
#app {
  font-family: "Jost", sans-serif;
}
button{
    border:none;
}
.dm-serif-display-regular {
    font-family: "DM Serif Display", serif;
    font-weight: 400;
    font-style: normal;
}

.dm-serif-display-regular-italic {
    font-family: "DM Serif Display", serif;
    font-weight: 400;
    font-style: italic;
}

.dm-serif-display-regular {
    font-family: "DM Serif Display", serif;
    font-weight: 400;
    font-style: normal;
}

.dm-serif-display-regular-italic {
    font-family: "DM Serif Display", serif;
    font-weight: 400;
    font-style: italic;
}

a{
    text-decoration: none;
}

.center {
    padding-left: calc(50% - 1200px/2);
    padding-right: calc(50% - 1200px/2);
}
.index {
    padding-left: calc(50% - 1200px/2);
    padding-right: calc(50% - 1200px/2);
}
</style>
