<script>
  import "../app.css"; 
  import Button from '$lib/Button.svelte'; 
</script>

<h1>Meu site</h1>

<ul>
  <li><a href="/">Inicio</a></li>
  <li><a href="/sobre">Sobre</a></li>
  <li><a href="/portfolio">Portfolio</a></li>
  <li><a href="/contato">Contato</a></li>
  <li><a href="/faq">Perguntas Frequentes</a></li>
</ul>

<Button label="clique aqui"></Button>
<Button label="clique 2"></Button>

<div>
  <h1 class="text-4xl font-bold text-blue-600 bg-gray-100 p-6 rounded-lg">
    Se isso aparecer azul, Tailwind está ok!
  </h1>
</div>
