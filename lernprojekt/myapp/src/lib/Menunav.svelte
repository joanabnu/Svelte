    <script>
  import { page } from "$app/state"
        import Logo from "$lib/Logo.svelte";
        const itens = [
            {href: '/', label:'Home'},
            {href: '/sobre', label:'Sobre'},
            {href: '/portfolio', label:'Portfolio'},
            {href: '/contato', label:'Contato'},
            {href: '/faq', label:'Perguntas Frequentes'},
        ]
       
    

    </script>    
        
        <a href="/">
        <Logo/></a>

        {#each   itens as {href,label} }
            <a {href} class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">{label}</a>
        {/each}
     <!-- <a href="/" class="text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-blue-500 mx-1.5 sm:mx-6" alt="Logo">Inicio</a>  -->
       

        

        <!-- <a href="/portfolio" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">Portfolio</a>

        <a href="/contato" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">Contato</a>

          <a href="/faq" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">Perguntas frequentes</a> -->
