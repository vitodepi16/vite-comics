<template>
    <div class="myContainer  container p-2 d-flex text-black">
        <div class="logo-container flex-start">
            <img src="../../public/img/dc-logo.png" alt="LogoSmall">
        </div>
        <div class="navbar flex-end">
            <ul v-for="(item,i) in listHeader"  > 
                <li class="text-uppercase">
                    <a href="item.url">{{ item.text }}</a>
                </li>
            </ul>
        </div>
    </div>
    <div>
        <div class="jumbotron">
            <img src="../../public/img/jumbotron.jpg" alt="">
        </div>
    </div>
</template>

<script>
        export default {
    name: 'HeaderDC',
    data() {
        return {
            listHeader: [
                {
                    text: 'characters',
                    url: '#'
                },
                {
                    text: 'comics',
                    url: '#'
                },
                {
                    text: 'movies',
                    url: '#'
                },
                {
                    text: 'tv',
                    url: '#'
                },
                {
                    text: 'games',
                    url: '#'
                },
                {
                    text: 'collectibles',
                    url: '#'
                },
                {
                    text: 'videos',
                    url: '#'
                },
                {
                    text: 'fans',
                    url: '#'
                },
                {
                    text: 'news',
                    url: '#'
                },
                {
                    text: 'shop',
                    url: '#'
                }
            ]
        }
    }
}
    
</script>

<style lang="scss" scoped>
.jumbotron{
   height: 350px ;
    img{
        width: 100%;
        height: 100%;
    }
}

</style>