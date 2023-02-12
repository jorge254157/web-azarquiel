<main>
    <div class="body">
        <nav>
            <div class="container">
                <div class="row" style="position: relative;">
                    <div class="col-sm-3 col-md-3">
                        <p><img class="image-responsive" src="/img/logoiesfseif.png" alt="logo"/></p>
                    </div>
                    <div class="col-sm-9 col-md-9" style="position: static;">
                        <ul class="menu">
                            <li class="li-l"><a href="http://www.ies-azarquiel.es/index.php">INICIO</a></li>
                            <li class="li-l"><a href="http://www.ies-azarquiel.es/index.php/al-dia">AL DÍA</a><i class="i-a fa-solid fa-chevron-down"></i></li>
                            <li class="li-l"><a href="http://www.ies-azarquiel.es/index.php/el-loro">EL LORO</a></li>
                            <li class="li-l"><a href="#">EL CENTRO</a><i class="i-a fa-solid fa-chevron-down"></i></li>
                            <li class="li-l"><a href="http://www.ies-azarquiel.es/index.php/secretaria">SECRETARÍA</a><i class="i-a fa-solid fa-chevron-down"></i></li>
                            <li class="li-l"><a href="#">FAMILIAS</a><i class="i-a fa-solid fa-chevron-down"></i></li>
                            <li class="li-l"><a href="http://www.ies-azarquiel.es/index.php/40-bolsa-de-trabajo">BOLSA</a></li>
                            <div class="boton">
                                <li class="li-ll"><button class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#demo">
                                    <i class="i-bar fa-solid fa-bars"></i>
                                </button></li>
                            </div>
                        </ul>
                    </div>
                    <div class="offcanvas offcanvas-end" id="demo">
                        <div class="offcanvas-header">
                          <h1 class="offcanvas-title">SEARCH</h1>
                          <button type="button" class="btn-close" data-bs-dismiss="offcanvas"></button>
                        </div>
                        <p><input type="text" placeholder="Search ..."></p>
                        <div class="offcanvas-body">
                            <p><i class="fa-solid fa-chevron-right"></i><a href="http://www.ies-azarquiel.es/index.php">INICIO</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="http://www.ies-azarquiel.es/index.php/al-dia">AL DÍA</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="http://www.ies-azarquiel.es/index.php/el-loro">EL LORO</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="#">EL CENTRO</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="http://www.ies-azarquiel.es/index.php/secretaria">SECRETARÍA</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="#">FAMILIAS</a></p>
                            <hr/>
                            <p><i class="fa-solid fa-chevron-right"></i><a href="http://www.ies-azarquiel.es/index.php/40-bolsa-de-trabajo">BOLSA</a></p>
                            <hr/>
                        </div>
                      </div>
                </div>
            </div>
        </nav>
    </div>
</main>

<style lang="sass">
    main
        font-family: 'Open Sans', sans-serif
    ul
        list-style: none
    li
        padding: 1px
        font-size: 14px
    i
        padding: 5px
        color: #999999
    a
        text-decoration: none
    img
        width: 100%
        height: 100%
        margin-top: 25px
        margin-bottom: 15px
    .menu
        display: flex
        justify-content: flex-end
        a
            text-decoration: none
            color: black
            &:hover
                color: #22b8f0
        li
            margin-top: 40px
            font-size: 12px
            padding: 0 10px
    nav
        box-shadow: 0 3px 3px rgb(0 0 0 / 5%)
    .i-a
        font-size: 10px
    .btn, .i-bar
        font-size: 14px
        color: black
        margin-top: -10px
    .offcanvas
        background-color: black
        color: white
    button
        background-color: white
    input
        background-color: black
        margin-left: 25px
        width: 325px
        color: white
    .offcanvas-body
        a
            text-decoration: none
            color: white
        p
            padding: 2px
            &:hover
                cursor: pointer
            i
                align-items: flex-end
                color: white
            
    @media screen and (max-width: 992px) 
        .li-ll
            display: block
        .li-l
            display: none
        .boton
            display: block
        .menu
            margin-top: -10px
        .img
            width: 100%
    @media screen and (max-width: 575px)
        img
            width: 50%
        .menu
            margin-top: -100px
</style>