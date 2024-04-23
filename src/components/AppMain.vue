<script>
import MusicVideo from './MusicVideo.vue';

export default {
    name: 'AppMain',
    components: {
        MusicVideo
    }
}
</script>

<template>
    <div class="main-content background-000">
        <img src="../assets/img/assets/image (1).png">
        <div class="main-info">
            <div class="info">
                <h3 class="active">INSTRUMENTAL ROCK</h3>
            </div>
            <div class="info">
                <h1>MUSIC IN THIS VIDEO</h1>
            </div>
            <div class="info">
                <button class="btn-more">READ MORE</button>
            </div>
        </div>

        <div class="main-card">
            <div class="single-card">
                <i class="fa-solid fa-guitar"></i>
                <h2>ORIGINAL IDEAS</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut sodales leo.</p>
            </div>
            <div class="single-card">
                <i class="fa-solid fa-compact-disc"></i>
                <h2>MUSIC STUDIO</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut sodales leo.</p>
            </div>
            <div class="single-card">
                <i class="fa-solid fa-headset"></i>
                <h2>ACOUSTIC COVERS</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut sodales leo.</p>
            </div>
        </div>
    </div>

    <div class="who-are background-000">
        <div class="the-jazz container-card">
            <h4 class="active space">WHO WE ARE</h4>
            <h1 class="space">SENSE THE JAZZ</h1>
            <p class="space">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
               Phasellus ut sodales leo. Duis id scelerisque nunc, ut aliquam elit.
               Suspendisse bibendum dui ut lacus dictum porta. Fusce malesuada risus ac mauris tincidunt, quis convallis mi venenatis. 
               Cras pretium feugiat mi sed commodo. Mauris placerat, ex egestas aliquet tincidunt, sem eros aliquam nisi, in suscipit dolor tortor a mi. 
               Nunc interdum nisi a feugiat iaculis.
            </p>
            <button class="btn-more space">READ MORE</button>
        </div>
    </div>

    <MusicVideo></MusicVideo>
</template>

<style scoped lang="scss">
.main-content{
    text-align: center;
    position: relative;
    img{
        width: 100%;
    }
    .info{
        margin: 40px 0;
    }
    h1{
        font-size: 70px;
    }
    .main-info{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -70%);
    }
    .main-card{
        position: absolute;
        top: 100%;
        left: 50%;
        transform: translate(-50%, -50%);
        display: flex;
        gap: 20px;
        .single-card{
            background-color:rgb(19, 19, 19);
            width: 350px;
            height: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            i{
                font-size: 80px;
                margin-bottom: 20px;
                border: 1px solid rgb(19, 19, 19);
                padding: 20px;
                border-radius: 50%;
            }
            h2{
                margin-bottom: 10px;
            }
            i:hover{
                color: #f2870c;
                border: 1px solid #f2870c;
                padding: 20px;
                border-radius: 50%;
            }
        }
    }
}
.the-jazz{
    text-align: center;
    padding: 300px 0 50px 0;
    .space{
        margin-bottom: 30px;
    }
    h1{
        font-size: 50px;
    }
    p{
        line-height: 1.5;
    }
}
</style>