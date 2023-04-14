<template>
    <div class="myContainer container">
        <div class="row">
            <CardComponent :thumb ="comics.thumb" :series="comics.series" :price="comics.price" :type="comics.type" v-for="(comics,index) in comics" :key="index"/>
        </div>
       
    </div>
    <navbarMain/>
</template> 

<script>
import {comics} from '../../data/data';
import navbarMain from './navbarMain.vue';
import CardComponent from './CardComponent.vue';
    export default {
        name: 'MainComponent',
        components:{
            CardComponent,
            navbarMain

        },
        data(){
            return{
                comics:[...comics]
            }
        }
    }
</script>

<style lang="scss" scoped>
.myContainer{
    padding: 2rem 0;
}
</style>