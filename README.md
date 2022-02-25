<html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
    <title></title>
    <style> 
    
        body {
          height: 100vh;
          font: 300 18px/1.6 "Source Sans Pro",sans-serif;
          text-align: center;
          background: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
	      }
	      
	    /*Menu Para Desktop*/
	    @media  (max-width: 1281px) {
        body {
          margin-left: 2px;
          margin-right:2px;
        }
        header {
          display: flex;
          align-items: center;
          box-sizing: border-box;
          height: 70px;
          padding: 1rem;
          justify-content: space-between;
          width: 100%;
          max-width: 980px;
        }
        #logo { /*Logo Vitor Oliveira*/
          margin-top:20px;
          font-weight: bold;
          font: 400 30px/1.6 "Source Sans Pro",sans-serif;
        }
        #borda { /*Borda na imagem principal*/
          height: 611px;
          width: 612px;
          align-items: center;
          display: block;
          margin-left: auto;
          margin-right: auto;
          border-width:5px;
          border-style:solid;
          border-color:#fff;
          border-radius:50%;
          
        }
        body ul { /*Lista*/
          margin: 0 auto;
          padding: 0 auto;
        }
        
        a { /*Links menu*/
          color: white;
          text-decoration: none;
          font: 370 18px/1.6 "Source Sans Pro",sans-serif;
        }
        
        a:hover { /*cor ao tocar nos links*/
          background:rgba(0, 0, 0, .09);
          background-color: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
        }
        
        
        p { /*parafrafos em geral*/
          text-align: justify;
          margin-left:  20px;
          margin-right:  20px;
          padding: 0 auto;
          color:#fff;
          font: 300 200%/1.6 "Source Sans Pro",sans-serif;
       }
       
       iframe  { /*yt videos*/
          border-radius:10px;
          width: 960px;
          height: 415px;
        }
        #img-dev2 {
         display: block;
         margin-left: 0 auto;
         margin-right: 0 auto ;
         width: 450px;
         height: 100px;
        
       }
       h2 { /*titulo imagem dev*/
         
         align-items: center;
         text-align: center;
         color:#fff;
         font: 300 50px/1.6 "Source Sans Pro",sans-serif;
       }
       /*estilo da imagem dev */
       
       #menu {
          display: flex;
          height: 8px;
          width: 90%;
          max-width: 980px;
          list-style: none;
          gap: .7rem;/*Coloca um espaçamento e separa os itens*/
        }
        #dev2 {
          height: 25px;
          width: 25px;
           
        }
        #programador {
          display: block;
          margin-left: 100px;
          width: 780px;
          height: 610px;
          
        }
        
       #menu a {
          width: 100%;
          max-width: 980px;
          display: block;
          padding-right: 70px;
          font: 400 100%/1.6 "Source Sans Pro",sans-serif;
        }
        /*escondendo o botão*/
        #btn-mobile {
          background: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
          outline: none;
          border:none;
          
        }
        .btn-up {
         color: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
     
       }
       #up-up { /*botão cima icone*/
         height: 50px;
         width: 50px;
         float: right;
         margin-top: 31px;
         margin-right: 1px;
      
       }
       #git-img { /*github icone*/
         height: 60px;
         width: 58px;
         float: left;
         margin-top: 27px;
         margin-right: 1px;
        
       }
       
       h3 { /*palavras do Rodapé*/
         font: 400 30px/1.6 "Source Sans Pro",sans-serif;
         color: black;
         padding: 0px;
         margin: 0px;
         margin-right: 32px;
         padding-top: 4px;
         padding-right: 10px;
       }
      footer { /*Rodapé*/
         margin-left: 0;
         padding-bottom: 20px;
         background-color: #fff;
         width: 100%;
         height: 2%;    
      } 
    
        
	  }  
      /*Menu para Versão Mobile*/
      @media  (max-width: 600px) {
          body {
             margin-left: 2px;
             margin-right:8px;
          }
          #logo {
            margin-top:5px;
            font-weight: bold;
            font: 300 35px/1.6 "Source Sans Pro",sans-serif;
          }

          #menu {
            display: block;
            position: absolute;
            width: 100%;
            top: 70px;
            right: 0px;
            margin-right: 28px;
            border-radius: 15px;
            background: linear-gradient(to bottom right, #9F00C5 ,#9370DB);
            transition: .6s;
            z-index: 1000;
            visibility: hidden;
            overflow-y: hidden;
          }
          
          #dev2 {
            height: 150px;
            width: 130px ;
            margin-top: 150px;
            margin-left: 20px;
          }
          
          #menu a {
            padding: 1rem 0;
            margin: 0 1rem;
            border-bottom: 3px solid white ;
            
          }
          
          #nav.active #menu {
            height: calc(100vh - 70px);
            visibility: visible;
            overflow-y: auto;
          }
          
          /*botão hamburguer*/
          #btn-mobile {
            width: 100%;
            max-width: 980px;
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
        
        #img-eu {
          height: 300px;
          width: 300px;
          align-items: center;
          display: block;
          margin-left: auto;
          margin-right: auto;
          border-radius: 20px;
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
        p {
          text-align: justify;
          margin-left:  20px;
          margin-right:  20px;
          padding: 0 auto;
          color:#fff;
          font: 300 20px/1.6 "Source Sans Pro",sans-serif;
        }
      
        iframe { /*yt videos*/
          border-radius:10px;
          width: 360px;
          height: 215px;
        }
        
       h2 {
         align-items: center;
         text-align: center;
         color:#fff;
         font: 300 28px/1.6 "Source Sans Pro",sans-serif;
       }

       /*estilo da imagem programador */
       #programador {
         display: block;
         margin-left: 0px ;
         margin-right: 0 auto ;
         width: 400px;
         height: 309px;
        
       }
      
       /*Estilo do botão up*/
       .btn-up {
         color: #100a1c;
           radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
           radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
     
       }
       #up-up { /*botão cima icone*/
         height: 30px;
         width: 30px;
         float: right;
         margin-top: 31px;
         margin-right: 1px;
      
       }
       #git-img { /*github icone*/
         height: 38px;
         width: 38px;
         float: left;
         margin-top: 27px;
         margin-right: 1px;
        
       }
       
       h3 { /*palavras do Rodapé*/
         font: 300 19px/1.6 "Source Sans Pro",sans-serif;
         color: black;
         padding: 0px;
         margin: 0px;
         margin-right: 32px;
         padding-top: 4px;
         padding-right: 10px;
       }
      footer { /*Rodapé*/
         margin-left: 0;
         padding-bottom: 20px;
         background-color: #fff;
         width: 100%;
         height: 2%;    
      } 
     }
    </style>
  </head>
    <body>
         <header>
          
           <a id="logo"  href="https://github.com/VitorDev01">Vitor Oliveira</a>
           
           <nav id="nav">
             <button aria-label="Abrir Menu" id="btn-mobile" aria-haspopup="true" aria-controls="menu" aria-expanded="false"><span id="pao"></span>
             </button>
             
             <ul id="menu" role="menu">
             <li><a href="https://github.com/VitorDev01">♔ Git Hub</a></li>
              
             <li><a href="https://www.instagram.com/vitorkw89/">♛ Instagram </a></li>
               
             <li><a href="https://wa.me/5524992717594">♘ Contato</a></li>
               
             <li><a href="https://github.com/VitorDev01?tab=repositories">♗ Projetos</a></li>
             
             <li><a href="https://vitordev01.github.io/404-page/">♖ Blog (em desenvolvimento)</a></li>
             <img id="dev2" src="dev2.png">
             </ul>
           </nav> 
        </header>
         <br>
         <div id="borda">
         <img id="img-eu" src="vitor.png">
         </div>
         
         <h2>♙</h2>
      
         <p>21 Anos, barramansanse, Desenvolvedor Front End, conhecimentos autodidata em HTML5 CSS3 e JavaScript, pretendo cursar Análise e Desenvolvimento De Sistemas , fã do raciocínio lógico  amo café e estou sempre buscando aperfeiçoar meu inglês.</p><br><p><p>Tendo começado essa jornada na programação em 2019 com os professores Gustavo Guanabara e Bruno Campos dos canais Curso em video e CFB cursos.</p>
        
         <br> <!--videos do Yt-->
          <iframe src="https://www.youtube.com/embed/rsFCVjr5yxc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
         <br><br>
         <iframe width="360" height="215" src="https://www.youtube.com/embed/lcKo-ycLDNw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
         
         <br>
           
         <h2>Desenvolvedor Front End</h2>
         
         <br>
         <img id="programador" src="dev.png">
         
         <br>
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
       <!--Imagens do Rodapé e botão up-->
       <a class="btn-up"href="#"> &#9651; <img id="up-up" src="up.png"></a>
       <a href="https://github.com/VitorDev01"><img id="git-img" src="git.png"></a>
       <footer>
       <h3>© 2022 VitorDev01 | GitHub Pages</h3>
       </footer>
    </body>
</html>
