<!-- Script JS -->
<script>
</script>

<!-- Estructura contenido HTML -->

<h1>PROYECTO ABACO (N°1)</h1>
<h2 id="centena"> Ficha azul = 100 </h2> <h2 id="decena">Ficha verde = 10</h2><h2 id="unidad">Ficha roja = 1</h2>



<!-- Abaco 1 -->

<div class="graph">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>

    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha1"></div>
</div>

<!-- Abaco 2 -->

<div class="graph" style="margin-top: 600px">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>

    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha2"></div>
    <div class="ficha" id="ficha3"></div>
    <div class="ficha" id="ficha4"></div>
    <div class="ficha" id="ficha5"></div>
    <div class="ficha" id="ficha6"></div>
    <div class="ficha" id="ficha7"></div>
    <div class="ficha" id="ficha8"></div>
</div>

<!-- Abaco 3 -->

<div class="graph" style="margin-top: 1200px">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>

    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha9"></div>
    <div class="ficha" id="ficha10"></div>
    <div class="ficha" id="ficha11"></div>
    <div class="ficha" id="ficha12"></div>
    <div class="ficha" id="ficha13"></div>
    <div class="ficha" id="ficha14"></div>
</div>

<!-- Abaco 4 -->

<div class="graph style=" style="margin-top: 1800px">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>



    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha15"></div>
    <div class="ficha" id="ficha16"></div>
    <div class="ficha" id="ficha17"></div>
    <div class="ficha" id="ficha18"></div>
    <div class="ficha" id="ficha19"></div>
    <div class="ficha" id="ficha20"></div>
    <div class="ficha" id="ficha21"></div>
    <div class="ficha" id="ficha22"></div>
</div>

<!-- Abaco 5 -->

<div class="graph style=" style="margin-top: 2400px">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>



    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha23"></div>
    <div class="ficha" id="ficha24"></div>
    <div class="ficha" id="ficha25"></div>
    <div class="ficha" id="ficha26"></div>
    <div class="ficha" id="ficha27"></div>
    <div class="ficha" id="ficha28"></div>
    <div class="ficha" id="ficha29"></div>
    <div class="ficha" id="ficha30"></div>
    <div class="ficha" id="ficha31"></div>
    <div class="ficha" id="ficha32"></div>
    <div class="ficha" id="ficha33"></div>
    <div class="ficha" id="ficha34"></div>
</div>

<!-- Abaco 6 -->

<div class="graph style=" style="margin-top: 3000px">
    <div class="cuadrado-madera" style="margin-top: 300px;"></div>
    <div class="palo" id="uno"></div>
    <div class="palo"  id="dos"></div>
    <div class="palo"  id="tres"></div>



    <!-- Fichas del abaco -->
    <div class="ficha" id="ficha35"></div>
</div>

<!-- Estilos CSS -->
<style> 

@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
h1{
    font-family: 'Press Start 2P', cursive;
    text-align: center;
    padding-top: 25px;
    padding-bottom: 50px;
    font-size: 100px;
    animation: cambioColor 5s infinite; /* Aplica la animación de cambio de color */
}

        @keyframes cambioColor {
            0% {
                color: red; /* Cambia el color del título a rojo */
            }
            10% {
                color: orange; /* Cambia el color del título a naranja */
            }
            20% {
                color: yellow; /* Cambia el color del título a amarillo */
            }
            30% {
                color: green; /* Cambia el color del título a verde */
            }
            40% {
                color: blue; /* Cambia el color del título a azul */
            }
            50% {
                color: indigo; /* Cambia el color del título a índigo */
            }
            60% {
                color: violet; /* Cambia el color del título a violeta */
            }
            70% {
                color: pink; /* Cambia el color del título a rosa */
            }
            80% {
                color: purple; /* Cambia el color del título a púrpura */
            }
            90% {
                color: cyan; /* Cambia el color del título a cian */
            }
            100% {
                color: red; /* Vuelve a cambiar el color del título a rojo */
            }
        }

#centena{
    font-family: 'Press Start 2P', cursive;
    text-align: center;
    padding-top: 25px;
    padding-bottom: 50px;
    font-size: 60px;    
    animation: cambioColorCentena 1s infinite;
    
}


#decena{
    font-family: 'Press Start 2P', cursive;
    text-align: center;
    padding-top: 25px;
    padding-bottom: 50px;
    font-size: 60px;    
    animation: cambioColorDecena 1s infinite;
    
}

#unidad{
    font-family: 'Press Start 2P', cursive;
    text-align: center;
    padding-top: 25px;
    padding-bottom: 50px;
    font-size: 60px;    
    animation: cambioColorUnidad 1s infinite;
    padding-bottom: 100px;
    
}

/* Animación para cambiar aleatoriamente el color del elemento h2 con id "centena" */
@keyframes cambioColorUnidad {
    0% { color: red; } /* Rojo */
    33% { color: #FF6347; } /* Tomate */
    66% { color: #DC143C; } /* Rojo carmesí */
    100% { color: red; } /* Vuelve a rojo */
}

/* Animación para cambiar aleatoriamente el color del elemento h2 con id "decena" */
@keyframes cambioColorDecena {
    0% { color: lime; } /* Verde */
    33% { color: #32CD32; } /* Lima */
    66% { color: #008000; } /* Verde bosque */
    100% { color: lime; } /* Vuelve a verde */
}

/* Animación para cambiar aleatoriamente el color del elemento h2 con id "unidad" */
@keyframes cambioColorCentena {
    0% { color: cyan; } /* Cian */
    33% { color: #00FFFF; } /* Cian claro */
    66% { color: #008B8B; } /* Cian oscuro */
    100% { color: cyan; } /* Vuelve a cian */
}

.graph {
    position: relative;
    margin: 0 auto;
    width: 900px; /* Ancho del cuadrado */
    margin-bottom: 500px;
    
}

.cuadrado-madera {
        width: 900px; /* Ancho del cuadrado */
        height: 70px; /* Altura del cuadrado */
        background-color: #E0974B; /* Color marrón oscuro similar a la madera */
        border: 2px solid #654321; /* Borde marrón más oscuro */
        position: absolute;
        border-radius: 10px;

}


    /* Define el estilo de los palos */
.palo {
        
        width: 15px; /* Ancho del palo */
        height: 300px; /* Altura del palo */
        background-color: #80543A;
        position: absolute;
        border-radius: 5% 5% 0 0;  /* Posición arriba del cuadrado */
}

/* Define la posición de los palos */
#uno {
    margin-left: 25%; /* Posición del primer palo */

}

#dos {
    margin-left: 50%; /* Posición del segundo palo */
}

#tres {
        margin-left: 75%; /* Posición del tercer palo */
}


/* Estilos para las fichas del ábaco */
.ficha {
        width: 150px; /* Ancho de la ficha */
        height: 20px; /* Altura de la ficha */
        position:absolute;
        border-radius: 5% 5% 5% 5%; /* Para que las fichas sean círculos */
        margin-bottom: 2px; /* Espacio entre las fichas */
        transform: translateX(-43%); /* Centra horizontalmente las fichas */
        
    }

    /* Posiciones de las fichas del ábaco */
    #ficha1 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -300px;
    }

    #ficha2 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -300px;
    }

    #ficha3 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -280px;
    }
    
    #ficha4 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -300px;
    }

    #ficha5 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -280px;
    }

    #ficha6 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -260px;
    }

    #ficha7 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -240px;
    }

    #ficha8 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -220px;
    }

    #ficha9 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -300px;
    }

    #ficha10 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -280px;
    }

    #ficha11 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -260px;
    }

    #ficha12 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -300px;
    }

    #ficha13 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -280px;
    }

    #ficha14 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -260px;
    }

    #ficha15 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -300px;
    }

    #ficha16 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -280px;
    }

    #ficha17 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -260px;
    }

    #ficha18 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -240px;
    }

    #ficha19 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -220px;
    }

    #ficha20 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -200px;
    }

    #ficha21 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -300px;
    }

    #ficha22 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -280px;
    }

    #ficha23 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -300px;
    }

    #ficha24 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -280px;
    }

    #ficha25 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -260px;
    }

    #ficha26 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -240px;
    }

    #ficha27 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -220px;
    }

    #ficha28 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -200px;
    }

    #ficha29 {
        background-color: #4CCB49;
        border: 1.5px solid #387d37;
        margin-left: 50%;
        bottom: -180px;
    }

    #ficha30 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -220px;
    }

    #ficha31 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -300px;
    }

    #ficha32 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -280px;
    }

    #ficha33 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -260px;
    }

    #ficha34 {
        background-color: #BE0167;
        border: 1.5px solid #751849;
        margin-left: 75%;
        bottom: -240px;
    }

    #ficha35 {
        background-color: #02ffea;
        border: 1.5px solid #02756b;
        margin-left: 25%;
        bottom: -300px;
    }
 

</style>

