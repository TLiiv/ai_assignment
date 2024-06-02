<script>
  // import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import Hero from "../components/Hero.svelte";
  import Sidebar from "../components/Sidebar.svelte";
</script>

<style>
  .container {
    display: flex;
    position: relative;
    width: 100%;
    min-height: 100vh;
  }

  .content {
    flex: 1;
    padding: 10px;
  }
</style>

<div class="container">
  <Sidebar />
  <div class="content">
    <Header/>
    <Hero /> 
  </div>
</div>
