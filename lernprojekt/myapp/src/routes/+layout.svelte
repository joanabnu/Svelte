
<script>
  import Navbar from "$lib/Navbar.svelte"
import "../app.css";

   
  // let message = "Tailwind está funcionando!";
</script>
<!-- 
<h1 class="text-3xl font-bold text-blue-500">{message}</h1> -->

<!-- <h1> Layout Inicio</h1> -->
<!-- <div> -->
<!-- <ul>
  <li ><a href="/"> Inicio </a></li>
    <li><a href="/sobre">Sobre</a></li>
    <li><a href="/portfolio">Portfolio </a></li>
    <li> <a href="/contato">Contato</a></li>
     <li><a href="/faq">Perguntas Frequentes </a></li>
</ul>
</div> -->
<!-- 
<h4>restante da pagina</h4>
<h1 class="text-3xl font-bold text-blue-500">Olá, Joana!</h1> -->


<Navbar/>
<slot/>
