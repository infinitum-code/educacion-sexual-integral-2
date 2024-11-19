<!DOCTYPE html>
<html lang="ESI">
<head>

<style>
body {
    background-color:#e1e5e7;
}
.home {
    display:flex ;
}
.in-flex {
    flex: 1;

}
.in-flex:first-child {
    flex: 2;
    padding:5 px;
   
    margin: 5px;

}
.in-flex div {
     padding:5 px;
     margin:5 px;
}
/*encabezado*/
header {
    background-color: #0288d1;
    color: #fff;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(239, 236, 236, 0.1);
}
/* Pie de página */
footer {
    background-color: #01579b;
    color: #fff;
    text-align: center;
    padding: 10px;
}      



/* Fondo Animado */
body {
    background: linear-gradient(45deg, #0288d1, #01579b, #ff6f00);
    background-size: 300% 300%;
    animation: gradientBackground 10s ease infinite;
}

/* Animación del Fondo */
 @keyframes gradientBackground {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}
/* Botón 3D */
button {
    background-color: #ff6f00;
    color: #fff;
    padding: 30px 50px;
    border: none;
    border-radius: 5px;
    box-shadow: 0 5px #d35400;
    font-size: 1.1em;
    cursor: pointer;
    transition: all 0.2s ease;
}

button:hover {
    box-shadow: 0 2px #d35400;
     transform: translateY(-3px);
}

button:active {
    box-shadow: 0 0 #d35400;
    transform: translateY(2px);
}
/* Texto con Efecto de Sombra y Brillo */
h1 {
    font-size: 5.5em;
    color: #fff;
    text-shadow: 0 0 20px rgba(255, 255, 255, 0.8), 0 0 20px #ff6f00, 0 0 30px #ffab00;
}
/* Enlaces con Efecto de Subrayado */
a {
    color: #0288d1;
    text-decoration: none;
    position: relative;
    transition: color 0.3s ease;
}

a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 5px;
    bottom: 0;
    left: 0;
    background-color: #ff6f00;
    transition: width 0.3s ease;
}

a:hover {
    color: #ff6f00;
}

a:hover::after {
    width: 100%;
}

</style>
        <head>
            <meta charset="UTF-8">
            <meta name="keywords" content="ESI,biologia,curpo humano,salud,">
            <meta name="description" content="Bienvenidos a nuestra página de Educación Sexual Integral (ESI), un espacio dedicado a brindar información precisa, inclusiva y completa sobre temas de sexualidad, salud y bienestar para todas las personas. Aquí podrás encontrar recursos y respuestas a tus dudas sobre el cuerpo humano, identidad de género, diversidad sexual, prevención de enfermedades, derechos sexuales y reproductivos, y mucho más.
             En este sitio, nos comprometemos a ofrecer un enfoque que respete y celebre la diversidad, incluyendo contenidos específicos para mujeres, hombres, personas no binarias y otras identidades. Nuestro objetivo es promover el respeto, el autocuidado, la igualdad y la toma de decisiones informadas a través de la educación.
             Explora nuestras secciones dedicadas, participa en nuestras actividades interactivas y descubre guías prácticas diseñadas para acompañarte en tu proceso de aprendizaje. Estamos aquí para apoyarte y brindarte la información que necesitas, sin tabúes y con la seriedad que la ESI merece.">
            <meta name="author" content="Joaquin Aranda">
            <meta name="robots" content="index">
             <link rel="stylesheet" href="styles.css">
            <link rel="shortcut icon" href="c:\Users\Estudiante\Downloads\logoesi.png">

            <body>

                
                <title>ESI</title> 

            <head></head><h1>ESI</h1></head>
            <link rel="stylesheet" type="text/css" href="estilo.css">
             <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <b><h3> <p>ESI significa (Educación Sexual Integral), un derecho de los niños, niñas y adolescentes de Argentina. Se trata de una política educativa que brinda información sobre la sexualidad y la salud sexual y reproductiva de los jóvenes.
        
        La ESI tiene como objetivo que los jóvenes adquieran los conocimientos, habilidades, actitudes y valores que les permitan: Proteger su salud, Desarrollar relaciones sociales y sexuales respetuosas, Tomar decisiones responsables, Comprender y proteger los derechos de los demás. 
         
        La ESI se imparte en las escuelas de todos los niveles, tanto públicas como privadas, y se adapta a cada etapa evolutiva. Por ejemplo, en el nivel inicial se enseña a reconocer las partes del cuerpo y prevenir abusos sexuales infantiles. 
         
        Algunos de los ejes conceptuales de la ESI son: El cuidado del cuerpo propio y ajeno, La valoración de la afectividad, La diversidad, El ejercicio de derechos, La perspectiva de género.</b></h3>
         </p>
     <H2><u>Elige tu genero:</u></H2>
    
    <h3>MASCULINO:</h3>
    <a href="informacion 1.html"><button>INFORMACION</button></a>
     <h3>FEMENINO:</h3>
     <a href="informacion 2.html"><BUTton>INFORMACION</BUTton></a>
     <h3>GENERO NO BINARIO:</h3>
     <a href="informacion 3.html"><button>INFORMACION</button></a>
  <br>
  <body>
    
    <section class="home">
        <div class="in-flex"></div>
        <div class="in-flex">
    </section> 
         
</body>
     
    
     

    </body>
    </html>
