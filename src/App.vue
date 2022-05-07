<template>
  <div>
    <Header/>
    <Navigation/>
    <HomePage/>
  </div>
</template>

<script>
import Header from './components/Header'
import Navigation from "@/components/Navigation";
import HomePage from "@/components/HomePage";

export default {
  name: 'App',

  components: {
    Header,
    // eslint-disable-next-line vue/no-unused-components
    Navigation,
    HomePage
  },

  data: () => ({
    //
  }),
};
</script>
