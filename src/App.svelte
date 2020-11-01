<script>
  import Footer from './components/Footer/index.svelte'
  import Header from './components/Header/index.svelte'
  import MainContainer from './components/MainContainer/index.svelte'
  import 'bulma/css/bulma.css'
  export let name;
</script>

<main class="flex h-screen flex-col">
  <Header/>
  <MainContainer/>
  <Footer/>
</main>

<style>
  @media (min-width: 1662px) {
    main {
      max-width: none;
    }
  }
</style>