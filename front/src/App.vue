<template>
  
  <Header />
  <Main :name="items[0].name" :price="items[0].price" />
  <Main name="りんご" price="100" />
  <Footer />
  <Axios />
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Main from "./components/Main.vue";
import Axios from "./components/Axios.vue"
export default {
  name: "App",
  components: {
    Header,
    Footer,
    Main,
    Axios
    
  },
  data: () => {
    return {
      // templateブロック内の2つ目のItemコンポーネントで使用しているデータです。
      items: [
        { name: 'ぶどう', price: 500 },
      ],
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
