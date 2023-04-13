
<template>
    <div class="bottom-footer">
        <div class="container d-flex justify-content-between">
            <div class="d-flex justify-content-between ">
                <button class="text-uppercase ">sign-up now!</button>
            </div>
            <div class="d-flex align-item-center flex-wrap ">
                <h4 class="text-uppercase m-0 px-3"> follow us</h4>

                <img src="/img/footer-facebook.png" alt="facebook">
                <img src="/img/footer-twitter.png" alt="twitter">
                <img src="/img/footer-youtube.png" alt="youtube">
                <img src="/img/footer-pinterest.png" alt="pinterest">
                <img src="/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
    </div>
</template>

<script>
export default {
  
    }

</script>

<style lang="scss" scoped>
.bottom-footer{
    background-color:#303030 ;
    padding: 2rem;
    h4{
        color:#0282f9;
    }
    button {
        background-color: transparent;
        border: 2px solid #0282f9;
        color: white;
        padding: .5rem;
    }
    img{
        margin-left: 30px;
    }
}
</style>