<template>
    <section id="categories">
      <div class="container">
        <ul>
            <li v-for="(el,i) in categories" :key="i" class="infoCat">
                <figure>
                    <img :src="el.src" alt="">
                </figure>
                {{ el.text }}
            </li>
        </ul>
      </div>
    </section>
</template>

<script>
export default {
  data(){
    return {
        categories:[
            {
                text:'Digital Comics',
                src:require('../assets/img/buy-comics-digital-comics.png')
            },
            {
                text:'DC Merchandise',
                src:require('../assets/img/buy-comics-merchandise.png')
            },
            {
                text:'Subscription',
                src:require('../assets/img/buy-comics-subscriptions.png')
            },
            {
                text:'Comic Shop Locator',
                src:require('../assets/img/buy-comics-shop-locator.png')
            },
            {
                text:'DC Power Visa',
                src:require('../assets/img/buy-dc-power-visa.svg')
            },
        ] 
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >

   #categories{
    background-color:#0282F9;
    color:whitesmoke;

    .container{


        ul{
            display: flex;
            justify-content: space-around;
            align-items: center;
            cursor: pointer;
            padding: 20px 0px;
            font-size:18px;
            

            figure{
                width:40px
            }

            .infoCat{
                text-align: center;
                text-transform: uppercase;
                display:flex;
                align-items: center;
                gap: 4px;
                
            }
        }
    }
    
  }
 
</style>