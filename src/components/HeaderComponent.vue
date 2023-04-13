<template>
    <div class="myContainer text-black">
        <div class="logo-container">
            <img src="../assets/img/dc-logo.png" alt="LogoSmall">
        </div>
        <div class="navbar">
            <ul v-for="(item,i) in listHeader"  > 
                <li class="text-uppercase">
                    <a href="item.url">{{ item.text }}</a>
                </li>
            </ul>
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

<style scoped>

</style>