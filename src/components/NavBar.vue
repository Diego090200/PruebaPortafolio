<template>
    <header class="header">
        <nav>
            <ul class="nav-links">
                <li><a class="links" href="#">Inicio</a></li>
                <li><a class="links" href="#">Proyectos</a></li>
                <li><a class="links" href="#">Educación y Habilidades</a></li>
                <li><a class="links" href="#">Blog</a></li>
                <li><a class="links" href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    .header{
        align-items: center;
        display: flex;
        flex-direction: row;
        gap: 12px;
        justify-content: flex-end;
        margin-right: 2%;
        margin-top: 1%;
        padding: 0px;
    }

    .header .nav-links li{
        display: inline-block;
        padding: 0 20px;
    }
    .links{
        color: #FFFFFF;
        font-family: 'Nunito', sans-serif;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 23px;
        padding: 7px;
        text-decoration: none;
    }

    .links:hover{
        background-color: #2C66C3;
        border-radius: 50px;
    }
</style>