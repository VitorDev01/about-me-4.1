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
        #centralize {
           margin-left: 6%;
           margin-right:2%;
          
        }
       
        body { 
           margin-left: 10px;
           margin-right:2%;
           padding-left: 1%;
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
          margin-top:30px;
          font-size: 100px;
          font: 400 50px/1.6 "Source Sans Pro",sans-serif;
        }
        
        #border {
          color: #fff;
          background: url(v.jpg);
          background-size: 450px 450px ;
          background-repeat: no-repeat;
          width: 450px;
          height: 450px;
          border:solid 3px;
          margin-left: auto;
          margin-right: auto;
          margin-top: 50px;
          border-radius: 20px 20px 20px 20px;
        }
        
        #borda { /*Borda na imagem principal*/
          border: none;
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
          width: 20px;
        }
        
        #img1, #img3, #img4 {
            height: 50px;
            width: 50px;
        }
        
        #img2 {
            height: 50px;
            width: 55px;
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
          visibility: visible;
          width: 760px;
          height: 415px;
          border-radius:10px;
        }
 
     
       h2 { /*titulo imagem dev*/
         
         align-items: center;
         text-align: center;
         color:#fff;
         font: 300 50px/1.6 "Source Sans Pro",sans-serif;
       }

       #menu {
          display: flex;
          height: 8px;
          width: 90%;
          max-width: 980px;
          list-style: none;
          gap: .7rem;/*Coloca um espaçamento e separa os itens*/
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
       
       h3 { /*palavras do Rodapé*/
         font: 400 30px/1.6 "Source Sans Pro",sans-serif;
         color: black;
         padding: 0px;
         margin: 0px;
         padding-left: 5px;
         padding-top: 10px;
         padding-right: 10px;
       }
       mark {
           background-color: #9F00C5;
        }
       footer { /*Rodapé*/
        /*esquerda left direita right*/
         margin-right: 100%;
         padding-bottom: 20px;
         background-color: #fff;
         width:108%;
         height: 50px;    
       } 
    
        
  }  
      /*Menu para Versão Mobile*/
      @media  (max-width: 767px) {
          #centralize {
             margin-left: 0px;
             margin-right: 0px;
          
          }
      
          body {
             margin-left: 2px;
             margin-right:8px;
             padding-left: 1%;
          }
    
          #logo {
            margin-top:5px;
            font-weight: bold;
            font: 300 35px/1.6 "Source Sans Pro",sans-serif;
          }
      
          #menu a { /*Links menu*/
            
            height: 0px;
            width: 20px;
            -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
            margin-left: 45%;
            margin-top: 50px;
            padding-top: 0px;
            text-decoration: none;
        
          }
          
          #menu li a {
             margin-top: 90px;
          }
            
          a:hover { /*cor ao tocar nos links*/
            background:rgba(0, 0, 0, 0);
          }
        
          #img1,#img2, #img3, #img4 {
            height: 50px;
            width: 50px;
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
          
          #border {
              color: #fff;
              background: url(v.jpg);
              background-size: 300px 300px ;
              background-repeat: no-repeat;
              width:300px;
              height:300px;
              border:solid 3px;
              margin-left: auto;
              margin-right: auto;
              margin-top: 20px;
              border-radius: 20px 20px 20px 20px;
          }
          
          hr {
             color: #fff;
             background-color: #fff;
             width: 350px;
          }
          hr {
             color: #fff;
             background-color: #fff;
             width: 350px;
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
            visibility: visible;
            width: 340px;
            height: 210px;
            border-radius:10px;
          }
        
          h2 {
            align-items: center;
            text-align: center;
            color:#fff;
            font: 300 28px/1.6 "Source Sans Pro",sans-serif;
          }

         h3 { /*palavras do Rodapé*/
            font: 300 19px/1.6 "Source Sans Pro",sans-serif;
            color: black;
            padding: 0px;
            margin: 0px;
            padding-left: 5px;
            padding-top: 4px;
            padding-right: 10px;
         }
         mark {
           background-color: #9F00C5;
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
             <li><a href="https://github.com/VitorDev01"><img id="img1"src="github.png"></a></li>
             
             <li><a href="mailto:victorskw89@gmail.com"><img id="img2" src="email.png"></a></li>
                          
             <li><a href="https://www.instagram.com/vitorkw89/"><img id="img3" src="insta.png"></a></li>
              
            <li><a href="https://www.facebook.com/profile.php?id=100078322466753"><img id="img4" src="Facebook.png"></a></li>  
            
             </ul>
           </nav> 
        </header>
         <br>
         
         <div id="border">
         </div>
         
         <div id="centralize">
         <br>
         <hr>
         </div>
  
         <p>Estudante de programação Front End, conhecimentos autodidata em HTML5 CSS3 e JavaScript, pretendo cursar Análise e Desenvolvimento De Sistemas , fã do raciocínio lógico  amo café e estou sempre buscando aperfeiçoar meu inglês.</p>
         <p>Tendo começado essa jornada na programação em 2019 com os professores Gustavo Guanabara e Bruno Campos dos canais Curso em video e CFB cursos.</p>
        
         <br> <!--videos do Yt-->
        
           
         <h2>Desenvolvedor Front End</h2>

         <iframe width="360" height="215" src="https://www.youtube.com/embed/WzZ1CSuFpb0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
         <br><br>
         <hr>
          <div id="borda"></div>
         
         <p>É responsável pela experiência do usuário dentro de uma aplicação web, é ele quem vai desenhar e desenvolver as páginas com as quais, posteriormente, o usuário irá interagir. </p>
         
        <p>Tendo como principal Linguagem de programação o JavaScript uma das três principais tecnologias da <mark><a href="https://vitordev01.github.io/page-about-internet/">World Wide Web.</a></mark> A grande maioria dos sites usa, e todos os principais navegadores têm um mecanismo JavaScript dedicado para executá-lo.</p>
         
        <br>
        </div>
        
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
      
       <footer>
       <h3>© 2022 VitorDev01 | GitHub Pages</h3>
       </footer>
    </body>
</html>
