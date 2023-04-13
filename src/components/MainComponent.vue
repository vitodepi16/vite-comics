<template>
    <div class="myContainer container text-center text-white">
        <h4>Contents go here</h4>
       
    </div>
    <navbarMain/>
</template> 

<script>
import navbarMain from './navbarMain.vue';
    export default {
        name: 'MainComponent',
        components:{
            navbarMain
        }
    }
</script>

<style lang="scss" scoped>
.myContainer{
    padding: 2rem 0;
}
</style>