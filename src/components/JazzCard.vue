<script>
export default {
    name: 'JazzCard',
    props: ['image','title']
}
</script>

<template>
    <div class="music-card">
        <div class="img-card">
            <img :src="image">
        </div>
        <div class="social-card">
            <h3>{{ title }}</h3>
            <p>Stream On:
                <i class="fa-brands fa-spotify"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-solid fa-music"></i>
                <i class="fa-solid fa-cloud"></i>
                <i class="fa-solid fa-compass"></i>
            </p>
        </div>
    </div>
</template>

<style scoped lang="scss">
.music-card{
    width: calc((100% / 3) - 15px);
    gap: 15px;
    margin: 20px 0 40px 0;
}
.img-card{
    img{
        width: 100%;
    }
}
.social-card{
    text-align: center;
    margin-top: 20px;
    p{
        display: flex;
        justify-content: center;
        margin-top: 10px;
        i{
            margin: 0 7px;
        }
        i:hover{
            color: #f2870c;
        }
    }
}

</style>