<script>
export default {
    name: 'AlbumOut'
}
</script>

<template>
    <div class="album-now background-000">
        <img src="../assets/img/assets/cms_parallax.jpg">

        <div class="album-info">
            <h3 class="ms-active ms-info">INSTRUMENTAL ROCK</h3>
            <h1 class="ms-info">ALBUM OUT NOW</h1>
            <button class="btn-more ms-info">READ MORE</button>
        </div>
    </div>
    <div class="album-awards">
        <img src="../assets/img/assets/counter_parallax.jpg">
        <div class="awards-info">
            <div>
                <i class="fa-solid fa-child-reaching"></i>
                <h2>163</h2>
                <h4>CONCERTS</h4>
            </div>
            <div>
                <i class="fa-solid fa-rocket"></i>
                <h2>145</h2>
                <h4>HAPPY CLIENTS</h4>
            </div>
            <div>
                <i class="fa-solid fa-trophy"></i>
                <h2>72</h2>
                <h4>MUSIC AWARDS</h4>
            </div>
            <div>
                <i class="fa-solid fa-music"></i>
                <h2>182</h2>
                <h4>TOTAL SONGS</h4>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.album-now{
    position: relative;
    img{
        width: 100%;
    }
    .album-info{
        width: 1100px;
        margin: 0 auto;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        h1{
            font-size: 70px;
        }
        .ms-info{
            margin: 30px 0;
        }
    }
}
.album-awards{
    position: relative;
    img{
        width: 100%;
    }
    overflow: hidden;
    height: 400px;
    .awards-info{
        display: flex;
        justify-content: space-between;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 800px;
        text-align: center;
        i{
            font-size: 70px;
            margin-bottom: 20px;
        }
        h2{
            font-size: 50px;
            margin-bottom: 20px;
        }
    }
}
</style>