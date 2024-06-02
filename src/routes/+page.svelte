<script>
  // import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import Hero from "../components/Hero.svelte";
  import Sidebar from "../components/Sidebar.svelte";
</script>


<div class="flex relative min-h-screen">
  <Sidebar />
  <div class="flex-1 p-2 ">
    <Header/>
    <Hero /> 
  </div>
</div>
