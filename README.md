# tarefa<!DOCTYPE html>
<html lang="en">
    <head>
        <title> CSS Template</title>
        <meta charset="utf-8">
        <meta name="viewport" content="widht=device-width, initial-scale=1">
    
    </head>
    <body>



        <header>
            <h2>Cidades</h2>
        </header>
        <section>
            <nav>
                <ul>
                 <li><a href="#">Santos</a></li>
                 <li><a href="#">Ubatuba</a></li> 
                 <li><a href="#">Limeira</a></li>    
                    </ul>
            </nav>
        <article>
            <h1> Santos</h1>
            <p>Dados da cidade de Santos</p>
            <p>Os setores do turismo, de serviços e da pesca em geral completam a lista de maiores atividades da economia santista. De um lado a economia pujante, de outro sua vocação para o lazer. Santos tem como principal atrativo os sete quilômetros de praia, acompanhados pelo maior jardim de orla do mundo - título concedido pelo Guinness World Records. </p>
        
            <article>
                <h1> Ubatuba</h1>
                <p>Dados da cidade de Ubatuba</p>
                <p>Mais informações da cidade e uma imagem...</p>
                </article>
                <article>
                    <h1> Limeira</h1>
                    <p>Dados da cidade de Limeira</p>
                    <p>Mais informações da cidade e uma imagem...</p>
                    </article>
            </article>
        </section>
         <footer>
            <p>Rodapé</p>
        </footer>
  
  
  
    </body>
</html>
<meta name="viewport"content="width=device-widht, Initial-scale=1">
<style>
  *  {
        box-sizing: border-box;
    }
    body {
        fant-family: Arial, Helvetica, sans-serif;
    }
    /* Style the header */
    header {
        background-color: #666;
        padding: 30px;
        text-align: center;
        font-size: 35px;
        color: white;

    }
    /* Container for flexboxes */
    section {
        display: -webkit-flex;
        display: flex;
        
    }
    /* Style the navigation menu */
    nav {
        -webkit-flex: 1;
        -ms-flex: 1;
        flex: 1;
        background: #ccc
        padding: 20px;
    }
    /* Style the list inside the menu */
    nav ul {
        list-style-type: none;
        padding: 0;
    
    }
    /* Style the content */
    article {
   -webkit-flex: 3;
   -ms-flex: 3;
   flex: 3;
   background-color: #f1f1f1;
   padding: 10px;
    }
    /* Style the footer */
    footer {
        background-color: #777;
        padding: 10px;
        text-align: center;
        color: white;
    }
    /* Layout reponsivo- do menu e do conteúdo dentro da seção.*/
    @media (max-widht: 600px) {
        section{
            -webkit-flex-direction: column;
            flex-direction: column;
        }
    }


</style>
