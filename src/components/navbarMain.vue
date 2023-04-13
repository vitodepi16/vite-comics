<template>
    <div class="navabarMain">
        <ul class="d-flex justify-content-center">
            <li class="d-flex align-items-center" v-for="(item) in liNavbar">
                    <div class="box-icons">
                        <img :src="'../../public/img/' + item.image" class="h-50" alt="">
                    </div>
                 <p class="icon-text text-uppercase"> {{ item.text }} </p>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
    name: 'navbarMain',
    data() {
        return {
            liNavbar: [
                {
                    image: 'buy-comics-digital-comics.png',
                    text: 'digital comics'
                },
                {
                    image: 'buy-comics-merchandise.png',
                    text: 'dc merchandise'
                },
                {
                    image: 'buy-comics-subscriptions.png',
                    text: 'subscriptions'
                },
                {
                    image: 'buy-comics-shop-locator.png',
                    text: 'comic shop locator'
                },
                {
                    image: 'buy-dc-power-visa.svg',
                    text: 'dc power visa'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.box-icons{
    width: 30px;
    margin-left: 15px;
    img{
        width: 100%;
    }
}

.icon-text{
    font-size: 15px;
    margin-left: 15px;

}
ul{
    padding: 40px;
    display: flex;
    flex-wrap: wrap;
}

</style>