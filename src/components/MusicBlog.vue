<script>
export default {
    name: 'MusicBlog'
}
</script>

<template>
    <div class="background-000">
        <div class="music-blog">
            <h4 class="active space">MUSIC BLOG</h4>
            <h1>BEST MUSIC BLOG</h1>
        </div>
        <div class="cont-card">
            <div class="card">
                <img src="../assets/img/assets/hip_hop_wired_to_dance_make.jpg">
                <h3>HIP HOP WIRED TO DANCE MAKE</h3>
                <p class="active"><i class="fa-regular fa-calendar-days"></i> 06 November 2021</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae faucibus massa. 
                   Fusce placerat ex id lacinia fermentum. 
                </p>
            </div>
            <div class="card">
                <img src="../assets/img/assets/music_business-worldwide.jpg">
                <h3>MUSIC BUSINESS WORLDWIDE</h3>
                <p class="active"><i class="fa-regular fa-calendar-days"></i> 27 May 2022</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae faucibus massa. 
                   Fusce placerat ex id lacinia fermentum. 
                </p>
            </div>
            <div class="card">
                <img src="../assets/img/assets/giveaways_rock.jpg">
                <h3>GIVEAWAYS ROCK TO ALL</h3>
                <p class="active"><i class="fa-regular fa-calendar-days"></i> 07 May 2022</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae faucibus massa. 
                   Fusce placerat ex id lacinia fermentum. 
                </p>
            </div>
        </div>

        <div class="jumbo-img">
            <div>
                <img src="../assets/img/assets/instagram_img4.jpg">
                <img src="../assets/img/assets/instagram_img5.jpg">
                <img src="../assets/img/assets/instagram_img6.jpg">
                <img src="../assets/img/assets/instagram_img7.jpg">
                <img src="../assets/img/assets/instagram_img8.jpg">
                <img src="../assets/img/assets/instagram_img9.jpg">
                <img src="../assets/img/assets/instagram_img10.jpg">
                <img src="../assets/img/assets/instagram_img1.jpg">
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.music-blog{
    text-align: center;
    padding-top: 100px;
    h1{
        font-size: 50px;
    }
}
.cont-card{
    width: 1100px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    padding: 50px 0 130px 0;
    .card{
        width: calc((100% / 3) - 15px);
        img{
            width: 100%;
        }
        h3{
            font-size: 20px;
            padding-top: 15px;
        }
        p{
            padding-top: 15px;
        }
        i{
            color: #f2870c;
        }
    }
}

.jumbo-img{
    width: 100%;
    img{
        width: calc(100% / 8);
        border: 1px solid black;
    }
}
</style>