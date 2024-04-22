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
            <button>READ MORE</button>
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
    button{
        color: white;
        background-color: transparent;
        border: 1px solid #f2870c;
        padding: 15px 40px;
    }
    button:hover{
        background-color: #f2870c;
    }
}
</style>