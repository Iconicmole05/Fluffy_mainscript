<!-- routify:options preload="proximity" -->
<script>
import Navbar from "../components/Navbar.svelte";
import Footer from "../components/Footer.svelte";
</script>


<div class="wrapper">
    <Navbar />
    <main>
      <slot />
    </main>
    <Footer />
  </div>
  
  <style>
    div.wrapper {
      max-width: 100%;
      overflow: hidden;
    }
    main {
      min-height: 90vh;
      padding: 1 8.5rem;
    }
  </style>