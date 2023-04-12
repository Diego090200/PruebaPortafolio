<template>
    <div class="educacion-habilidad">
        <!-- Contenedor para la informacion respecto a educacion -->
        <div class="educacion">
            <div class="titulo">
                Educación
            </div>
            <div class="edu-info">
                Actualmente estoy terminando mis estudios universitarios en la Universidad Rafael Landivar, Campus de Quetzaltenango, en el trayecto de mi vida educativa e desarrollado habilidades para el diseño de aplicaciones web y de escritorio, personalmente se me facilita el trabajo en equipo y la comunicación con mis compañeros.
            </div>
            <button id="open" class="abrir">Ver informacion</button>
            <!-- Contenedor para modal de informacion académica -->
            <div class="modal-container" id="modal_container">
                <div class="modal">
                    <h1>Educación</h1>
                    <div class="nl-academico">
                        <h4 class="sub-title">Nivel academico</h4>
                        <p>Actualmente tengo 9 semestres cursados en la carrera de Ingeniería en Informática y Sistemas</p>
                    </div>
                    <div class="logros">
                        <h4 class="sub-title">Información extracurricular</h4>
                        <ul class="listado-logros">
                            <li><a>Participación del curso de Docker desde 0 impartido por la empresa LaserAnts de Quetzaltenango.</a></li>
                            <li><a>Participación en la conferencia de parte de ESET Antivirus, acerca de la Seguridad en Dispositivos.</a></li>
                            <li><a>Participación en el XV Simposio de Ingeniería denominado Ingeniería que transforma al mundo, Universidad Rafael Landívar Campus de Quetzaltenango.</a></li>
                            <li><a>Participación en el XIV Simposio de Ingeniería denominado Evolución para trascender, Universidad Rafael Landívar Campus de Quetzaltenango.</a></li>
                            <li><a>Participación en el XIII Simposio de Ingeniería denominado Innovación, retos y oportunidades, Universidad Rafael Landívar Campus de Quetzaltenango.</a></li>
                            <li><a>Participación en el XII Simposio de Ingeniería denominado Ingenio y optimización, Universidad Rafael Landívar Campus de Quetzaltenango.</a></li>
                            <li><a>Participación en el XI Simposio de Ingeniería sobre la Calidad en la Ingeniería, Universidad Rafael Landívar Campus de Quetzaltenango.</a></li>
                            <li><a>Participación en el taller de parte de Señor Xplorer, acerca de Reparación de Computadores y conexiones web.</a></li>
                        </ul>
                    </div>
                        <button id="close" class="cerrar">Cerrar</button>
                </div>
            </div>
        </div>
        <!-- Contenedor para la informacion respecto a mis habilidades -->
        <div class="habilidades">
            <div class="titulo">
                Habilidades
            </div>
            <div class="habilidades-info">
                <div class="html">
                    <img src="/img/tecnologias/html.png" alt="HTML" class="logo-tecnologia">
                    HTML
                </div>
                <div class="css">
                    <img src="/img/tecnologias/css.png" alt="CSS" class="logo-tecnologia">
                    CSS
                </div>
                <div class="typescript">
                    <img src="/img/tecnologias/typescript.png" alt="TS" class="logo-tecnologia">
                    TypeScript
                </div>
                <div class="javascript">
                    <img src="/img/tecnologias/javascript.png" alt="JS" class="logo-tecnologia">
                    JavaScript
                </div>
                <div class="react">
                    <img src="/img/tecnologias/reactjs.png" alt="React" class="logo-tecnologia">
                    React
                </div>
                <div class="vue">
                    <img src="/img/tecnologias/vue.png" alt="Vue" class="logo-tecnologia">
                    Vue
                </div>
                <div class="java">
                    <img src="/img/tecnologias/Java.png" alt="Java" class="logo-tecnologia">
                    Java
                </div>
                <div class="python">
                    <img src="/img/tecnologias/Python.png" alt="Python" class="logo-tecnologia">
                    Python
                </div>
                <div class="mongo">
                    <img src="/img/tecnologias/mongodb.png" alt="MongoDB" class="logo-tecnologia">
                    MongoDB
                </div>
                <div class="mysql">
                    <img src="/img/tecnologias/mssql.png" alt="MySQL" class="logo-tecnologia">
                    MySQL
                </div>
                <div class="git">
                    <img src="/img/tecnologias/git.png" alt="Git" class="logo-tecnologia">
                    Git
                </div>
                <div class="figma">
                    <img src="/img/tecnologias/figma.png" alt="Figma" class="logo-tecnologia">
                    Figma
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
    /* Estilos para el contenedor de educacion y habilidades*/
    .educacion-habilidad{
        align-items: center;
        color: #FFFFFF;
        display: flex;
        flex-direction: column;
        font-family: 'Nunito', sans-serif;
        font-style: normal;
        line-height: 23px;
        margin-top: 100px;
    }

    /* Estilos para el contenedor de educacion*/
    .educacion{
        align-items: center;
        display: flex;
        flex-direction: column;
        gap: 10px;
        justify-content: center;
        padding: 10px;
    }

    /* Estilos para la informacion de la educacion*/
    .edu-info{
        align-items: center;
        display: flex;
        flex-direction: row;
        font-size: 23px;
        gap: 10px;
        height: 136px;
        justify-content: center;
        padding: 10px;
        text-align: justify;
        width: 1002px;
    }

    /* Estilos para el boton que muestra la informacion de educacion*/
    .abrir{
        align-items: center;
        background: #2C66C3;
        border-radius: 4px;
        color: #FFFFFF;
        display: flex;
        flex-direction: row;
        gap: 10px;
        height: 47px;
        justify-content: center;
        padding: 10px;
        width: 208px;
    }

    /* Estilos para el boton que muestra la informacion de educacion*/
    .cerrar{
        background: #2C66C3;
        border-radius: 4px;
        color: #FFFFFF;
        gap: 10px;
        height: 47px;
        margin-top: 10px;
        padding: 10px;
        width: 208px;
    }
    /* Estilos para ventana de la informacion de la educacion*/
    .modal-container{
        align-items: center;
        background-color: #293548;
        display: flex;
        height: 100vh;
        justify-content: center;
        left: 0;
        opacity: 0;
        position: fixed;
        top: 0;
        width: 100vw;
    }

    /* Estilos para la informacion de la educacion*/
    .modal{
        background-color: rgba(0, 0, 0, 0.3);
        border-radius: 5px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        height: 80%;
        max-width: 100%;
        overflow: auto;
        padding: 30px 50px;
        width: 600px;
    }

    /* Estilos para informacion academica*/
    .nl-academico{
        align-items: flex-start;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        margin: 0;
        text-align: start;
    }

    /* Estilos para logros extracurriculares*/
    .logros{
        display: flex;
        flex-direction: column;
        margin: 0;
        text-align: start;
    }

    /* Estilos para el listado de los logros extracurriculares*/
    .listado-logros{
        display: flex;
        flex-direction: column;
        margin-top: 10px;
        text-align: start;
    }

    /* Estilos para subtitulos*/
    .sub-title{
        margin: 0;
    }

    /* Estilos para los titulos*/
    .titulo{
        font-size: 40px;
        margin-bottom: 10px;
    }

    /* Estilos para el contenedor de habilidades*/
    .habilidades{
        align-items: center;
        display: flex;
        flex-direction: column;
        justify-items: center;
        margin-top: 110px;
    }

    /* Estilos para las tecnologias de habilidades*/
    .habilidades-info{
        align-items: center;
        display: grid;
        font-size: 32px;
        grid-template-columns: 25% 25% 25% 25% ;
        grid-template-rows: 128px 128px 128px;
        justify-items: center;
        margin-top: 10px;
        width: 1022px;
    }

    /* Posicionamiento para las tecnologias en el grid*/
    .html {
        grid-column: 1;
        grid-row: 1;
    }
    .css{
        grid-column: 2;
        grid-row: 1;
    }
    .typescript{
        grid-column: 3;
        grid-row: 1;
    }
    .javascript{
        grid-column: 4;
        grid-row: 1;
    }
    .react{
        grid-column: 1;
        grid-row: 2;
    }
    .vue{
        grid-column: 2;
        grid-row: 2;
    }
    .java{
        grid-column: 3;
        grid-row: 2;
    }
    .python{
        grid-column: 4;
        grid-row: 2;
    }
    .mongo{
        grid-column: 1;
        grid-row: 3;
    }
    .mysql{
        grid-column: 2;
        grid-row: 3;
    }
    .git{
        grid-column: 3;
        grid-row: 3;
    }
    .figma{
        grid-column: 4;
        grid-row: 3;
    }

    /* Estilos para los contenedores de cada tecnologia*/
    .html, .css, .typescript, .javascript, .react, .vue, .java, .python, .mongo, .mysql, .git, .figma{
        align-items: center;
        border-radius: 8px;
        border: 3px solid #293548;
        display: flex;
        height: 60px;
        justify-content: center;
        width: 200px;
    }

    /* Definicion de tamaño para las imagenes de las tecnologias*/
    .logo-tecnologia{
        height: 35px;
        margin-right: 2px;
        width: 35px;
    }
</style>