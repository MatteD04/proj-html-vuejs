<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="background-000">
        <div class="ms-container ms-header-menu">
            <div>
                <img src="../assets/img/assets/Logo.png">
            </div>
            <div class="ms-nav-menu">
                <ul>
                    <li class="ms-active">HOME</li>
                    <li><a href="#">BLOG</a></li>
                    <li>
                        <div class="dropdown">
                            <a href="#">EVENTS<i class="fa-solid fa-angle-down ms-arrow-click"></i></a>
                            <div class="dropdown-content">
                                <p>CHORAL MUSIC</p>
                                <p>CONCERT BRAND</p>
                                <p>OPERA CONCERTS</p>
                                <p>SYMPHONY ORCHESTRA</p>
                                <p>FAMILY CONCERTS</p>
                            </div>
                        </div>
                    </li>
                    <li><a href="#">GALLERY</a></li>
                    <li><a href="#">ABOUT US</a></li>
                    <li><a href="#">CONTACT US</a></li>
                    <li><a href="#">SHOP<i class="fa-solid fa-angle-down ms-arrow-click"></i></a></li>
                    <li><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a></li>
                    </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.ms-header-menu{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
}
.ms-nav-menu{
    ul{
        display: flex;
        align-items: center;
        gap: 30px;
        list-style: none;
        a{
            text-decoration: none;
            color: white;
        }
        
    }
    .ms-arrow-click{
        font-size: 12px;
        margin-left: 5px;
    }
    .dropdown {
        position: relative;
        display: inline-block;
    }

    .dropdown-content {
        display: none;
        position: absolute;
        background-color: #2b2b2b;
        width: 250px;
        padding: 5px 10px;
        z-index: 1;
        margin-top: 35px;
    }
    .dropdown:hover .dropdown-content {
        display: block;
    }
}
</style>