<template>
    <div class="col-12 col-md-6 col-sm-4 col-lg-3">
        <div class="card p-2 bg-black mt-4">
            <div class="card-body ">
                <div class="card-img">
                    <img :src="thumb" :alt="series" class="img-fluid">
                </div>
                <div class="card-title card-text">
                    {{ series }}  
                     <p class="price"> Prezzo:{{ price }}</p>
                        <p>Type:{{ type }}</p>
                </div>
             
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CardComponent',
        props: ['thumb','series', 'price', 'type'] 
    }
</script>

<style lang="scss" scoped>
.card-text{
    color:#797979;
}
</style>