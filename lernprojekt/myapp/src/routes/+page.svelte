<script>
  import "../app.css"; 
  import Button from '$lib/Button.svelte'; 
  import Teste from '$lib/Teste.svelte'

  import {name} from '$lib/store'


   
  const lista = [
    'Joana',
    'Maria',
    'Luz'
  ]
  const elementos = [
    {nome:'joao',idade:23},
    {nome:'maria',idade:29}
  ]
  
  for(let item of elementos){
    console.log(item)
  }
for(let nome of lista){
  console.log(nome)
}
  const idade = 24;


</script>

<h1>Meu site / Inicio</h1>
 {#if idade == 24}
 <p>Idade é 24</p>
{/if}

{#each lista as nome}
<p>{nome}</p>
{/each}

{#each elementos as item}
<p>{item.nome}  tem {item.idade} anos</p>
{/each} 

<Button label="clique aqui"></Button>
<Button label="clique 2"></Button> 
 <Teste/> 
<div>
  <h1 class="text-4xl font-bold text-blue-600 bg-gray-100 p-6 rounded-lg">
    Se isso aparecer azul, Tailwind está ok!
  </h1>
</div> 

<!-- {$name} -->
