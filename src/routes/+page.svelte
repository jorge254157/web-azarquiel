<main>
    <h1>Cursos de Especialización</h1>
    <div class="container">
        <a href="/videojuegos">
            <div class="imagen">
                <img class="imgs" src="/img/videojuegos.jpg" alt="videojuegos">
                <div class="info">
                    <h3>Videojuegos</h3>
                    <p>Curso de Especialización. Desarrollo de Videojuegos y Realidad Virtual</p>
                </div>
            </div>
        </a>
        <a href="/ciberseguridad">
            <div class="imagen">
                <img class="imgs" src="/img/ciber.jpg" alt="ciberseguridad">
                <div class="info">
                    <h3>Ciberseguridad</h3>
                    <p>Curso de Especialización. Principales técnicas y herramientas sobre la seguridad en informática</p>
                </div>
            </div>
        </a>
    </div>
</main>

<style lang="sass">
    h1
        text-align: center
        margin-top: 35px
    .container
        display: flex
    .info
        position: absolute
        top: 0
        margin-top: 25%
        color: white
        text-align: center
        display: none
    .imgs
        max-width: 100%
        height: 100%
        overflow: hidden
        &:hover
            -webkit-transform: scale(0.95)
            transform: scale(0.95)
            filter: blur(5px)
    .imagen
        margin: 25px
        position: relative
        max-width: 100%
        height: 500px
        overflow: hidden
        cursor: pointer
        border-radius: 6px
        transition: all .5s ease-in-out
        &:hover
            .info
                display: block
                text-align: center
                font-family: Arial, Helvetica, sans-serif
                margin-left: 50px
                margin-right: 50px
        @media screen and (max-width: 767px)
            
</style>