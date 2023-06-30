<script>
  import Header from "./lib/Header.svelte";
  import Main_content from "./lib/Main_content.svelte";
  import Sidebar from "./lib/Sidebar.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Footer from "./lib/Footer.svelte";
</script>

<div class="container">
  <Header />
  <Navbar />
  <Main_content />
  <Sidebar />
  <Footer />
</div>

<style>


  div.container {
    width: 100%;
    display: grid;
    gap: 20px;
    grid-template-columns: auto auto auto;
  }
</style>
