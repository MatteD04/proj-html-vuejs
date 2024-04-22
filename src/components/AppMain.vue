<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <div class="main-content">
        <div>
            <h3 class="active">INSTRUMENTAL ROCK</h3>
        </div>
        <div>
            <h1>MUSIC IN THIS VIDEO</h1>
        </div>
        <div>
            <button class="btn-more">READ MORE</button>
        </div>
    </div>
</template>

<style scoped lang="scss">
.main-content{
    background-image: url(../assets/img/assets/cms_parallax.jpg);
    padding: 200px 0;
    text-align: center;
    color: white;
    div{
        margin: 40px 0;
    }
    h1{
        font-size: 70px;
    }
}
</style>