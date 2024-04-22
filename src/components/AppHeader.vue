<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="header-menu container">
        <div>
            <img src="../assets/img/assets/Logo.png">
        </div>
        <div class="nav-menu">
            <ul>
                <li>ciao</li>
                <li>ciao</li>
                <li>ciao</li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container{
    width: 1400px;
    margin: 0 auto;
}
.header-menu{
    display: flex;
    justify-content: space-between;
    padding: 20px 0;
}
.nav-menu{
    ul{
        display: flex;
        align-items: center;
        gap: 10px;
        color: #ffffff;
        list-style: none;
    }
}
</style>