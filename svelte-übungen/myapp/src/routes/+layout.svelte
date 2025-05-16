
<script>
import "../app.css";
   
  let message = "Tailwind está funcionando!";
</script>

<h1 class="text-3xl font-bold text-blue-500">{message}</h1>

<h1> Layout</h1>
<ul>
    <li><a href="/sobre">Sobre</a></li>
    <li><a href="/portfolio">Portfolio </a></li>
    <li> <a href="/contato">Contato</a></li>
</ul>
<h4>restante da pagina</h4>
<h1 class="text-3xl font-bold text-blue-500">Olá, Joana!</h1>

<slot></slot>
