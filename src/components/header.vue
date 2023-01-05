<template>
    <header class="nav border-b-2 p-4 md:fixed w-[100%] ">
        <div class="flex flex-col md:flex-row justify-between items-center">
            <a href="#hero">
                <h1 class="text-2xl md:text-4xl font-MartianMono">Transit.Corp</h1>
            </a>
            <!-- <img class="w-" src="/assets/img/logo.png" alt=""> -->
            <div id="menu" class=" w-[100%] justify-content-end justify-end space-x-10 mr-5 text-xl hidden md:flex">
                <div class="item-menu">
                    <a href="#hero">HOME</a>
                </div>
                <div class="item-menu">
                    <a href="">ABOUT</a>
                </div>
                <div class="item-menu">
                    <a href="">PROJECT</a>
                </div>
                <div class="item-menu">
                    <a href="">SERVICE</a>
                </div>
                
            </div>


            <!-- Menu Mobile -->
            <div id="menuIcons" class="border-t-2 shadow-xl fixed bottom-0 w-full rounded-t-full md:hidden">
                <div id="MenuItems" class="flex flex-row justify-center p-2 space-x-2 text-xl">
                    <div id="itemsIcons" class="grid text-center p-2 rounded-full">
                        <a href="">
                            <font-awesome-icon icon="fa-solid fa-house" />
                        </a>
                        <a href="#">Home</a>
                    </div>
                    <div id="itemsIcons" class="grid text-center p-2 rounded-full">
                        <a href="">
                            <font-awesome-icon icon="fa-solid fa-address-card" />
                        </a>
                        <a href="">About</a>
                    </div>
                    <div id="itemsIcons" class="grid text-center p-2 rounded-full">
                        <a href="">
                            <font-awesome-icon icon="fa-solid fa-pen" />
                        </a>
                        <a href="">Project</a>
                    </div>
                    <div id="itemsIcons" class="grid text-center p-2 rounded-full">
                        <a href="">
                            <font-awesome-icon icon="fa-solid fa-swatchbook" />
                        </a>
                        <a href="">Service</a>
                    </div>
                    
                    
                </div>
            </div>
            <!-- End Menu Mobile -->

        </div>
    </header>
</template>

<script>

</script>

<style>

#menu .item-menu a{
    position: relative;
    display: inline-block
}

#menu .item-menu a::before{
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 2px;
    height: 2px;
    background-color: #0000FF;
    border-radius: 4px;
    scale: 0;
    transform-origin: left;
    transition: scale 0.30s;
}

#menu .item-menu a:hover:before{
    scale: 1;
}

#menuIcons #itemsIcons a:link{
    color:blue;
}


</style>