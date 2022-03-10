<template>
  <div class="comics">

    <figure class="comicImg">
      <img :src="srcThumb" alt="">
    </figure>

    <h4 class="comicTitle">{{ title }}</h4>

  </div>
</template>

<script>
export default {
    props:{
        srcThumb:{
            type: String,
            required: true
        },
        title:{
            type: String,
            required: true
        },
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .comics{

        .comicImg{

            img{
                display:block;
                aspect-ratio:1/1;
                object-fit:cover;
                object-position: center;
                width:100%;
            }
        }
        .comicTitle{
            text-transform: uppercase;
            font-size: 12px;
            height:20px;
            color:white
        }
            
    }

  

</style>
