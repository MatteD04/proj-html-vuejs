<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="background-000">
        <div class="container header-menu">
            <div>
                <img src="../assets/img/assets/Logo.png">
            </div>
            <div class="nav-menu">
                <ul>
                    <li class="active">HOME</li>
                    <li><a href="#">BLOG</a></li>
                    <li><a href="#">EVENTS</a></li>
                    <li><a href="#">GALLERY</a></li>
                    <li><a href="#">ABOUT US</a></li>
                    <li><a href="#">CONTACT US</a></li>
                    <li><a href="#">SHOP</a></li>
                    <li><a href="#">🔍</a></li>
                    </ul>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.header-menu{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
}
.nav-menu{
    ul{
        display: flex;
        align-items: center;
        gap: 30px;
        list-style: none;
        a{
            text-decoration: none;
            color: #ffffff;
        }
        
    }
}
</style>