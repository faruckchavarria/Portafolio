# Creacion de mi portafolio de servicio

#### primero creamos la cabecera de nuestra pagina de portafolio donde se contenera una frase,y una imagen, para crear este resultado usaremos el siguiente codigo:

```
  <header id="header">
        <h1>Mi portafolio de servicio</h1>
        <br>
        <img id="portafolio" src="img\338.png" width="500px" height="500px">
    </header>
```
luego de haber agregado esta informacion, podemos comenzar a agregar infromcion en lo que es nuestro portafolio el cual seria mi experiencia el cual utilice tablas y encabezados para llenarla de informacion y una imagen antes de la informacion para que no sea totalmente informacion y mucho texto.
```
<img id="perfil" src="img\WhatsApp Image 2020-06-08 at 12.05.37 PM.jpeg">
                <fieldset style="border: 0px;">
                    <legend>Algunas de mis experiencias</legend>
                    <table>
                        <p>Practicas Pre-profesionales en la universidad de las regiones autonomas de la costa caribe nicaraguense
                            URACCAN-Las Minas, en el area de tecnologia educativa</p>
                            <tr>
                                <td>
                                    Administración de la plataforma virtual universitaria en Moodle 3.4
                                </td>
                                <tr>  
                                <table>
                                <p>Implementacion de cableado estructurado en las oficinas de UNEN Las Minas</p>
                                </tr>
                                </tr>
                                <tr>
                                <td>Taller: de Capacitación de robótica LEGO EV3 (Universidad de las regiones autónomas de la costa caribe nicaragüense, 2018)</td>
                                </tr>
                                <tr>
                                <td>Certificación de robótica tetrix (Universidad De Las Regiones Autónomas De La Costa Caribe Nicaragüense)</td>
                                </tr>
                    <tr>
            <td>Certificación en Innovation sprint, por la universidad ITESO y TELCOR, CARCIP</td>
      </tr>
```
Los resultados pueden ser comprobados en el archivo punto HTML y CSS donde se utilizo lo necesario para darle ajustes.
 de la misma forma podemos hacer el procedimiento para el apartado de datos adicionales que esta compuesta por tablas e informacion de igual manera comparto parte del codigo:
 ```
 <h2 id="H3">Datos Adicionales</h2>
                    <br>
                    <img id="Datos_Adicionales" src="img\datosdeinteres_publicaciones.png" width="200" height="100">
                    <fieldset style="border: 0px;">
                        <legend> Lista de Eventos</legend>
                        <table>
                            <p>Olimpiadas de robotica</p>
                            <tr>
                                <td>Segunda olimpiada nacional de robótica 2018, Word robot olympiad, Nicaragua, ONR comtech.</td>
                            </tr>
                        </table>
                        <table>
                            <p>Rally Latinoamericano 2019</p>
                            <tr>
                                <td>Rally Latinoamericano de Innovación 2019, URACCAN recinto - Las minas</td>
                            </tr>
                        </table>
                        <table>
                            <p>Lanzamiento de robotica</p>
                            <tr>
                                <td>Lanzamiento nacional de robotica con la nueva categoria de Tetrix</td>
                            </tr>
                        </table>
 ``` 
 para crear el menu de navegacion a distintos apartados en el mismo documento lo hacemos con la etiqueta ```<nav>``` para saber que es un menu de navegacion, luego usamos la etiqueta ```<ul>``` para crear una lista no ordenada pero dentro de esa etiqueta usamos ```<li>``` para agregar un item de forma ordenada y por ultimo una etiqueta ```<a href="#">Titulo</a></li>``` para agregar el vinculo a una parte del documento.
 ```
     <section>
                        <nav id="nav"></nav>
                        <div id="navegador"></div>
                        <ul id="navegador ul"></ul>
                        <h3>Menu</h3>
                        <li id="navegador li"><a href="#">inicio</a></li>
                        <li id="navegador li"><a href="#H2">mi experiencia</a></li>
                        <li id="navegador li"><a href="#H3">Datos Adicionales</a></li>
                        <li id="navegador li"><a href="#H4">Recomendaciones</a></li>
                    </section>
 ```
 Luego solo nos quedaria lo que es el footer o el derecho de autor que esta al final de la pagina que usamos la etiqueta footer, la cual se usa de la siguiente manera:
  ```
 <footer id="footer">
                
                    <p>Todos los derechos reservados © Faruck Chavarria 2020</p>
                    <br>
                    </div>
                </ul>
            </footer>
   ```
Y claro para el CSS use varias cosas las cuales las compartire ahora mismo para darle estilo al documento.
```
*
{
    margin: 0%;
    padding: 0%;
}
html
{
min-height: 100%;
position: relative;
}
div
{
background-color:gray;
border: 0px white;
padding: 10px;
width: 85%;
margin: 0 auto;
}
#perfil
{
border-radius: 50;
margin-bottom: 12px;
margin-right: 30px;
width: 200px;
height: 200px;
display: block;
margin: auto;
}
#portafolio
{
    display: block;
    margin: auto;    
}
#fotoencabesado
{
    display: block;
    margin: auto;  
}
#Datos_Adicionales
{
    display: block;
    margin: auto;  
}
#header
{
padding: 50px;
text-align: center;
background: rgb(214, 133, 147);
color: white;
font-size: 30px;
margin: 0px;
font-size: 18px;
line-height: 25px;
}

a{

 text-decoration: none;
}
li
{
    margin-left: 20px;
}
#navegador li{
    display: inline;
    text-align: center;
    margin: 0 10px 0 0;
    }
p, h1, h2, fieldset, legend
{
    font-family: Georgia, 'Times New Roman', Times, serif;
}
legend
{
    background-color:#4a555c;
padding: 5px;
border-radius: 20px;
font-weight: bold;
}
#footer 
{
position: absolute;
left: 0;
right: 0;
bottom: 0;
width: 100%;
background-color: black;
color: white;
text-align: center;
}
th, td {
    border-bottom: 1px solid #ddd;
  }
  body
{
    background-color: plum;
}
#recomendacion
{
    display: block;
    margin: auto; 
}
p
{
    
    font-weight: bold;
    border-bottom: 1px solid #ddd;
}
```
