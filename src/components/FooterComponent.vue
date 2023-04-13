
<template>
    <div class=" list-container">
        <div class="container p-5">
            <div class="box-list">
                   <ul v-for="(item,index) in footerList" class="text-uppercase ms-3">
                     <h3>{{ item.title }}</h3>
                     <li v-for="(list) in item.liList" class="fs-6"><a href="">{{ list.text}} </a> </li>
                 </ul>
            </div>
             
                 
        </div>


    </div>
    <FooterBottom/>
</template>

<script>
import FooterBottom from './FooterBottomComponent.vue'

   export default {
    
    name: 'FooterComponent',
    data() {
        return {
            footerList: [
                {
                    title: 'dc comics',
                    liList: [
                        {
                            text: 'Characters',
                            url: '#'
                        },
                        {
                            text: 'Comics',
                            url: '#'
                        },
                        {
                            text: 'Movies',
                            url: '#'
                        },
                        {
                            text: 'Tv',
                            url: '#'
                        },
                        {
                            text: 'Games',
                            url: '#'
                        },
                        {
                            text: 'Videos',
                            url: '#'
                        },
                        {
                            text: 'News',
                            url: '#'
                        }
                    ]
                },
                {
                    title: 'dc',
                    liList: [
                        {
                            text: 'Terms Of Use',
                            url: '#'
                        },
                        {
                            text: 'Privacy policy (New)',
                            url: '#'
                        },
                        {
                            text: 'Ad Choices',
                            url: '#'
                        },
                        {
                            text: 'Advertising',
                            url: '#'
                        },
                        {
                            text: 'Jobs',
                            url: '#'
                        },
                        {
                            text: 'Subscriptions',
                            url: '#'
                        },
                        {
                            text: 'Talent Workshops',
                            url: '#'
                        },
                        {
                            text: 'CPSC Certificates',
                            url: '#'
                        },
                        {
                            text: 'Ratings',
                            url: '#'
                        },
                        {
                            text: 'Shop Help',
                            url: '#'
                        },
                        {
                            text: 'Contact Us',
                            url: '#'
                        }
                    ]
                },
                {
                    title: 'sites',
                    liList: [
                        {
                            text: 'DC',
                            url: '#'
                        },
                        {
                            text: 'MAD Magazine',
                            url: '#'
                        },
                        {
                            text: 'DC Kids',
                            url: '#'
                        },
                        {
                            text: 'DC Universe',
                            url: '#'
                        },
                        {
                            text: 'DC Power Visa',
                            url: '#'
                        }
                    ]
                },
                {
                    title: 'shop',
                    liList: [
                        {
                            text: 'Shop DC',
                            url: '#'
                        },
                        {
                            text: 'Shop DC Collectibles',
                            url: '#'
                        }
                    ]
                },
            ]
        }
    },
    components: {
        FooterBottom
    }
        }

</script>

<style lang="scss" scoped>
.list-container{
background-image: url('../../public/img/footer-bg.jpg');
background-size: cover;
margin: 0;
}
ul{
    color: white;
    margin: 0;
    list-style: none;
    li{
        color: #797979;
    }
}
.box-list{
    width: 60%;
    display: flex;
    flex-wrap: wrap;
}
</style>