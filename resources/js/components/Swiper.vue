<template>
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="../../../public/assets/images/image1.png" class="d-block w-100" width="100%" height="1000" alt="...">
<!--                <iframe id="header__background" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"  width="100%" height="360" src="https://www.youtube.com/embed/5iAKKiofkFw?autoplay=1&amp;playsinline=1&amp;controls=0&amp;loop=1&amp;playlist=5iAKKiofkFw&amp;enablejsapi=1&amp;origin=https%3A%2F%2Fwww.emporiumautomoveis.com.br&amp;widgetid=1"></iframe>-->
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Some representative placeholder content for the first slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="../../../public/assets/images/image2.png" class="d-block w-100" width="100%" height="1000" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="../../../public/assets/images/image3.png" class="d-block w-100" width="100%" height="1000" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<script>
export default {
    name: "swiper"
}
</script>

<style scoped>


</style>
