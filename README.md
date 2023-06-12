* {
    margin: 0;
    padding:0;
    box-sizing: border-box;
    font-family: Helvetica, sans-serif;
}

.row{
    display: flex;
    height: 100vh;
}
.s1{
    width: 10%;
    background-color: aqua;
}
.s8{
    width: 80%;
    background-color: crimson;
}

@media only screen and (max-width:768px){
    .row{
        display: block;
    }
    [class*="s-1"]{
        width: 100%;
        background-color: aqua;

    }
    [class*="s-8"]{
        width: 100%;
        background-color:crimson;
        
    }
}<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="blue">
    <p>La inteligencia artificial es una aliada perfecta del médico durante todo el proceso asistencial.
         Por una parte, contribuye al diagnóstico y detección temprana de enfermedades a través del análisis
          de grandes cantidades de datos de salud como el historial médico, 
        imágenes médicas o resultados de pruebas clínicas. 
    </p>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="Salmon">
    <p>Inteligencia Artificial Para Diagnósticos Precoces</p>
    
</body>
</html><!DOCTYPE html> 
 <html lang="en"> 
 <head> 
     <meta charset="UTF-8"> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
     <title>Document</title> 
 </head> 
 <body bgcolor="Salmon"> 
     <p>Inteligencia Artificial Para Diagnósticos Precoces</p> 
  
 </body> 
 </html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="Pink">
    <p>Un grupo de ingenieros de la Escuela de Ingeniería de USC Viterbi (Estados Unidos) 
        ha desarrollado un algoritmo que está llamado a revolucionar los métodos de diagnóstico médico,
         según sus creadores. 
        El responsable de este trabajo es el investigador Gerald Loeb, que partió de un sistema
         ideado para identificar objetos de forma precisa.
         Los resultados de este trabajo, que obtuvo una precisión del 95%, le han llevado a diseñar otro orientado
         a mejorar la atención médica y a reducir los gastos médicos.
        </p>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<frame id="frmSuperior" name="frmSuperior" src="Pagina1.HTML"/>
<frameSet cols="150,*">
    <frame id="frmIzquierda" name="frmIzquierda" src="Pagina2.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="Ques es.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="Que hacen.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="NuevosMetodos.HTML"/>
</frameSet>
>
<frameSet cols="25%,*25%">
    <frame src="Pagina2.HTML"/>
    <frame src="Ques es.HTML"/>
    <frame src="Que hacen.HTML"/>
    <frame src="NuevosMetodos.HTML"/>
<frameSet>
    <noframes>
<body> Su Nvegador No Soporta Frames</body>
    </noframes>
    </frameSet>

</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<frame id="frmSuperior" name="frmSuperior" src="Pagina1.HTML"/>
<frameSet cols="150,*">
    <frame id="frmIzquierda" name="frmIzquierda" src="Pagina2.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="Ques es.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="Que hacen.HTML"/>
<frame
id="frmCuerpo" name="frmCuerpo" src="NuevosMetodos.HTML"/>
</frameSet>
>
<frameSet cols="25%,*25%">
    <frame src="Pagina2.HTML"/>
    <frame src="Ques es.HTML"/>
    <frame src="Que hacen.HTML"/>
    <frame src="NuevosMetodos.HTML"/>
<frameSet>
    <noframes>
<body> Su Nvegador No Soporta Frames</body>
    </noframes>
    </frameSet>

</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proycto</title>
  <link rel="stylesheet" href="style.css">
</head>
<body bgcolor="pink">
  <table bgcolor="lighblue" style="width:100%; border: 6px;;">
  <th <li><a href="FRAME.HTML">Información</a></li></th>
  <th <li><a href="Imagenes.html">Imagenes</a></li></th>
  <th <li><a href="Video.html">Video Y Audio</a></li></th>
  <th <li><a href="Creditos.html">Creditos</a></li></th>
  </table>
  <svg width="200" height="250" viewBox="0 0 250 250">
    <defs>
      <radialGradient id="degradadoRadial5">
         <stop offset="50%" stop-color="#fff"></stop>
         <stop offset="100%" stop-color="#000"></stop>
         </radialGradient>
         <mask id="maskCirculo5">
            <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle>
            <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle>
            <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle>
            <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle>
     </mask>
    </defs>
   <image xlink:href="diagnostico medico.jpg" height="240" width="250" style="mask: url(#maskCirculo5);"></image>
   </svg>
   <div class="row">
    <div class="col s-8">
      <img src="Gift.gif">
    </div>
   </div>
</body>
</html>### AL ### 
 #Template for AL projects for Dynamics 365 Business Central 
 #launch.json folder 
 .vscode/ 
 #Cache folder 
 .alcache/ 
 #Symbols folder 
 .alpackages/ 
 #Snapshots folder 
 .snapshots/ 
 #Testing Output folder 
 .output/ 
 #Extension App-file 
 *.app 
 #Rapid Application Development File 
 rad.json 
 #Translation Base-file 
 *.g.xlf 
 #License-file 
 *.flf 
 #Test results file 
 TestResults.xml<!DOCTYPE html> 
 <html lang="en"> 
 <head> 
     <meta charset="UTF-8"> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
     <title>Document</title> 
 </head> 
 <body bgcolor="Pink"> 
     <p>Un grupo de ingenieros de la Escuela de Ingeniería de USC Viterbi (Estados Unidos)  
         ha desarrollado un algoritmo que está llamado a revolucionar los métodos de diagnóstico médico, 
          según sus creadores.  
         El responsable de este trabajo es el investigador Gerald Loeb, que partió de un sistema 
          ideado para identificar objetos de forma precisa. 
          Los resultados de este trabajo, que obtuvo una precisión del 95%, le han llevado a diseñar otro orientado 
          a mejorar la atención médica y a reducir los gastos médicos. 
         </p> 
  
 </body> 
 </html><!DOCTYPE html> 
 <html lang="en"> 
 <head> 
     <meta charset="UTF-8"> 
     <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
     <title>Creditos</title> 
 </head> 
 <style> 
     div{ 
         width: 150px; 
         height: 100px; 
         background-color: blue; 
         font-weight: bold; 
         position: relative; 
         animation: mymove 5s infinite; 
     } 
     #div1{animation-timing-function: linear;} 
     #div2{animation-timing-function: ease;} 
     @keyframes mymove{ 
         from{left: 0px;} 
         to{left: 300px;} 
         0%{background-color: red;} 
         25%{background-color: orange;} 
         50%{background-color: yellow;} 
         75%{background-color: green;} 
         100%{background-color: blue;} 
     } 
 </style> 
 <body bgcolor="lighblue"> 
     <h1>Creditos</h1> 
     <div id="div1">Yazmin Berenice Jiménez Aguilar</div> 
     <div id="div2">Karla Elizabeth Juarez Garcia</div> 
  
     <a href="mailto:jyazmin415@gmail.com"> 
         <img src = "gmail.jpg".jpg width="150" title="next page"><br> 
         <br> 
         </a> 
     <a href="https://www.facebook.com/yazmin.jimenez.5243817"> 
         <img src="Facebook.png".jpg width="150" title="next page"><br> 
         </a> 
     <a href="https://instagram.com/yazminjmz11?igshid=MzNlNGNkZWQ4Mg=="> 
      <img src="Instagram.jpg".jpg width="150" title="next page"><br> 
  
     </a> 
  <input type="datetime-local"> 
 </body> 
 </html><!DOCTYPE html> 
 <html lang="en"> 
 <head> 
   <meta charset="UTF-8"> 
   <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
   <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
   <title>Proycto</title> 
   <link rel="stylesheet" href="style.css"> 
 </head> 
 <body bgcolor="pink"> 
   <table bgcolor="lighblue" style="width:100%; border: 6px;;"> 
   <th <li><a href="FRAME.HTML">Información</a></li></th> 
   <th <li><a href="Imagenes.html">Imagenes</a></li></th> 
   <th <li><a href="Video.html">Video Y Audio</a></li></th> 
   <th <li><a href="Creditos.html">Creditos</a></li></th> 
   </table> 
   <svg width="200" height="250" viewBox="0 0 250 250"> 
     <defs> 
       <radialGradient id="degradadoRadial5"> 
          <stop offset="50%" stop-color="#fff"></stop> 
          <stop offset="100%" stop-color="#000"></stop> 
          </radialGradient> 
          <mask id="maskCirculo5"> 
             <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle> 
             <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle> 
             <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle> 
             <circle cx="125" cy="125" r="100" fill="url(#degradadoRadial5)"></circle> 
      </mask> 
     </defs> 
    <image xlink:href="diagnostico medico.jpg" height="240" width="250" style="mask: url(#maskCirculo5);"></image> 
    </svg> 
    <div class="row"> 
     <div class="col s-8"> 
       <img src="Gift.gif"> 
     </div> 
    </div> 
 </body> 
 </html>
