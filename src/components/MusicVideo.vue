<script>
export default {
    name: 'MusicVideo'
}
</script>

<template>
    <div class="new-video background-000">
        <img class="video-img" src="../assets/img/assets/video.jpg">
    
        <div class="play-video">
            <i class="fa-solid fa-caret-right"></i>
            <h1>NEW MUSIC VIDEO</h1>
        </div>
    </div>
    
</template>

<style scoped lang="scss">
.new-video{
    position: relative;
    .video-img{
        width: 100%;
    }
}
.play-video{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    i{
        font-size: 50px;
        color: #f2870c;
        border: 4px solid #f2870c;
        padding: 15px 27px;
        border-radius: 50%;
        margin-bottom: 30px;
    }
    h1{
        font-size: 50px;
    }
}
</style>