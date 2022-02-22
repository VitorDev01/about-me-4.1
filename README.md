<html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
    <title></title>
    <style> 
       
        html {
           background: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
          
           color: #6cacc5;
           
        }    
        body {
	        color: #6cacc5;
          font: 300 18px/1.6 "Source Sans Pro",sans-serif;
          margin: 0 ;
          padding: 0;
          text-align: center;
	     
	      }
        body ul {
          margin: 0 auto;
          padding: 0 auto;
        }
        a {
          color: white;
          text-decoration: none;
          font: 300 18px/1.6 "Source Sans Pro",sans-serif;
        }
        a:hover {
          background:rgba(0, 0, 0, .05);
        }
        
        #logo {
          margin-top:5px;
          font-weight: bold; /*atributo que engraça as letras*/
          font-weight: bold; /*atributo que engraça as letras*/
          font: 300 35px/1.6 "Source Sans Pro",sans-serif;
        }
        
        #header {
          box-sizing: border-box;
          height: 70px;
          padding: 1rem; /*para distancear o conteúdo da margem esquerda da pagina*/
          display: flex;
          align-items: center;
          justify-content: space-between;
          background: none;

        }
        #menu {
          display: flex;
          height: 8px;
          list-style: none;
          gap: .7rem;/*Coloca um espaçamento e separa os itens*/
          
        }
        #menu a {
          display: block;
          padding-right: 70px;
    
        }
        
        /*Menu para Versão Mobile*/
        @media (max-width: 600px) {

          #menu {
            display: block;
            position: absolute;
            width: 100%;
            top: 70px;
            right: 0px;
            background-color:#8A2BE2;
            transition: .6s;
            z-index: 1000;
            height: 0px;
            visibility: hidden;
            overflow-y: hidden;
          }
          #nav.active #menu {
            height: calc(100vh - 70px);
            visibility: visible;
            overflow-y: auto;
          }
          #menu a {
            padding: 1rem 0;
            margin: 0 1rem;
            border-bottom: 2px solid white ;
          }
          /*botão hamburguer aqui*/
          #btn-mobile {
            height: 40px;
            outline:none;
            margin-top:15px;
            display: flex;
            padding: .5rem 1rem;
            font-size: 1rem;
            gap: .5rem;
            border-radius: 20px;
            border: none;
            background: none;
            
          }
          #pao {
            width: 30px;
            height: 3px;
            border-top: 3px solid;
            color:white;
          }
          #pao::after {
            content: '';
            display: block;
            width: 30px;
            height: 3px;
            background: white;
            margin-top: 5px;
            transition: .3s;
            position:relative;
            background:currentColor;
          }
          #pao::before {
            content: '';
            display: block;
            width: 30px;
            height: 3px;
            background: white;
            margin-top: 5px;
            transition: .2s;
            position:relative;
            background:currentColor;
          }
          #nav.active #pao {
            
            border-top-color: transparent;
          }
          #nav.active #pao::before {
            transform: rotate(135deg);
          }
          #nav.active #pao::after {
             transform: rotate(-135deg);
             top: -8px;
          }  
        }
        #img {
          
          height: 300px;
          width: 300px;
          align-items: center;
          display: block;
          margin-left: auto;
          margin-right: auto;
          border-radius: 20px;
          
        }
  
       p {
          
          text-align: justify;
          margin-left:  20px;
          margin-right:  20px;
          padding: 0 auto;
          color:#fff;
          font: 300 20px/1.6 "Source Sans Pro",sans-serif;
          
       }
       h2 {
         
         align-items: center;
         text-align: center;
         color:#fff;
         font: 300 28px/1.6 "Source Sans Pro",sans-serif;
       }
       p2 {
         
          text-align: center;
          color:#fff;
          font: 300 18px/1.6 "Source Sans Pro",sans-serif;
          font: 300 18px/1.6 "Source Sans Pro",sans-serif;
       } 
       p4 {
          color: red;
          font: 300 20px/1.6 "Source Sans Pro",sans-serif;
          margin: 0 ;
          padding: 0;
          text-align: center;
       }
       p5 {
          color: black;
          font: 300 20px/1.6 "Source Sans Pro",sans-serif;
          margin: 0 ;
          padding: 0;
          text-align: center;
       }
       /*Esitlo da imagem e textos*/
       .conteiner {
         display: flex;
         margin-left: auto;
         margin-right: auto;
         justify-content: center;
         align-items: center;
         /*conteiner*/
         position: relative;
         width: 100px;
         flex-wrap: wrap;
         padding: 30px;
       }
       .conteiner .card {
         position: relative;
         max-width: 350px;
         height: 430px;
         background: #fff;
         margin: 30px 10px;
         padding: 20px 15px;
         display: flex;
         flex-direction: column;
         transition: 0.3s ease-in-out;
         border-radius: 10px;
       }
       .conteiner .card .imgBx {
         position: relative;
         width: 260px;
         height: 260px;
         top: -60px;
         left:20px;
         box-shadow: 0 5px 20px rgba(0,0,0,0.2);
         border-radius: 10px;
       }
       .conteiner .card .imgBx img {
         max-width: 100%;
         border-radius: 10px ;
       }
       .container .card. .content {
         position: center;
         margin-top: -140px;
         padding: 10px 15px;
       }
       
       /*estilo da imagem */
       #imgdev {
         display: block;
         margin-left: auto;
         margin-right: auto ; 
         width: 300px;
         height: 300px;
        
       }
       /*Estilo da Letra do Rodapé*/
       h3 {
         float: left;
         text-align:  center;
         color:#fff;
         font-size: 10px;
         font-family: serif;
       }
       #borda {
          height: 300px;
          width: 300px;
          align-items: center;
          display: block;
          margin-left: auto;
          margin-right: auto;
          border-width:4px;
          border-style:solid;
          border-color:#fff;
          border-radius:50%;
          
       }
       iframe {
         display: block;
         margin-left: auto;
         margin-right: auto ; 
         
       }
       /*Estilo do Rodapé*/
     /*  footer {
         margin: 0 auto;
         padding: 0 auto;
         bottom: 0;
         background-color: #fff;
         width: 100%;
         height: 40px;    
         text-align: center;
         line-height: 100px;
      } */
    </style>
  </head>
    <body>
         <header id="header"><!--tag do cabeçalho-->
          
           <a id="logo"  href="https://github.com/VitorDev01">Vitor Oliveira</a>
           
           <nav id="nav">
             <button aria-label="Abrir Menu" id="btn-mobile" aria-haspopup="true" aria-controls="menu" aria-expanded="false"><span id="pao"></span>
             </button>
            
             <ul id="menu" role="menu">
             <li><a href="https://github.com/VitorDev01">♛ Git Hub</a></li>
              
             <li><a href="https://www.instagram.com/vitorkw89/">♘ Instagram </a></li>
               
             <li><a href="https://wa.me/5524992717594">♖ Contato</a></li>
               
             <li><a href="https://github.com/VitorDev01?tab=repositories">♔ Projetos</a></li>
             
             <li><a href="https://vitordev01.github.io/404-page/">! <p4>Coca</p4>•<p5>Cola</p5> Gratis !</a></li>
             </ul>
           </nav> 
        </header>
         <br><br>
         <div id="borda">
         <img id="img" src="vitor.png">
         </div>
         
         <h2>♙</h2>
      
         <p>21 Anos, barramansanse, Desenvolvedor Front End, conhecimentos autodidata em HTML5 CSS3 e JavaScript, pretendo cursar Análise e Desenvolvimento De Sistemas , fã do raciocínio lógico  amo café e estou sempre buscando aperfeiçoar meu inglês.</p><br><p><p>Tendo começado essa jornada na programação em 2019 com os professores <a href="https://www.instagram.com/cursoemvideo/"><b>Gustavo Guanabara</b></a> e <a href="https://www.instagram.com/cfbcursos/?hl=pt"><b>Bruno Campos</b></a>.</p>
        
         <br><br>
        
         <h2>Desenvolvedor Front End</h2>
         
         <br>
         <img id="imgdev" src="dev.jpg">
         
         <p>É responsável pela experiência do usuário dentro de uma aplicação web, é ele quem vai desenhar e desenvolver as páginas com as quais, posteriormente, o usuário irá interagir. 
         <br>
        <p>Tendo como principal Linguagem de programação o JavaScript uma das três principais tecnologias da World Wide Web.A grande maioria dos sites usa, e todos os principais navegadores têm um mecanismo JavaScript dedicado para executá-lo.</p>
         </p>
        <br>
     
       <!--comandos Javascript-->
       <script>
        const btnMobile = document.getElementById('btn-mobile');
       
        function toggleMenu(event) {
         
          if (event.type === 'touchstart') event.preventDefault();
         
          const nav = document.getElementById('nav');
          
          nav.classList.toggle('active');
          
          const active = nav.classList.contains('active');
          
          event.currentTarget.setAttribute('aria-expanded' , active);
          
          if (active) {
            event.currentTarget.setAttribute('aria-label' , 'Fechar Menu');
        
          } else {
            event.currentTarget.setAttribute('aria-label' , 'Abrir Menu');
          }
        }
        
        btnMobile.addEventListener('click' , toggleMenu);
        
        btnMobile.addEventListener('touchstart' , toggleMenu);
       
       </script>
    </dody>
</html>
