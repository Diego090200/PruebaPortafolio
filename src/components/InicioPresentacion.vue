<template>
    <div class="informacion">
        <div class="sobre-mi">
            <div class="info-1">
                Hola soy
            </div>
            <div class="info-2">
                Diego Hernández
            </div>
            <div class="info-3">
                &lt;Ingeniero en informática y sistemas/&gt;
            </div>
            <div class="info-4">
                Soy una persona con deseos de superación y disposición para el aprendizaje. Poseo habilidades para diseño web, organización, planificación y trabajar en equipo. Me considero alguien proactivo, dinámico, responsable y con excelentes relaciones humanas.
            </div>
        </div>
        <img class="perfil" src="/img/Perfil.jpg" alt="Imagen de Perfil">
    </div>
</template>

<style scoped>

    .informacion{
        align-items: center;
        display: flex;
        flex-direction: row;
        gap: 100px;
        justify-content: center;
        padding: 150px 24px 40px;
    }
    .info-1, .info-2, .info-3, .info-4{
        color: #FFFFFF;
        font-family: 'Nunito', sans-serif;
        font-style: normal;
        font-weight: 400px;
        line-height: 23px;
        padding: 7px;
        width: 591px;
    }

    .perfil{
        border-radius:150px;
        height:300px;
        width:300px;
    }

    .info-1{
        font-size: 32px;
        margin-top: 3%;
    }
    .info-2{
        font-size: 64px;
        margin-top: 2%;
    }
    .info-3{
        color: #2CB67D;
        font-size: 32px;
        margin-top: 3%;

    }
    .info-4{
        font-size: 20px;
        margin-top: 1%;
    }
</style>