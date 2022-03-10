<template>
  <div class="main-header">
    <div class="container">

      <!-- img -->
      <figure class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </figure>

      <!-- link -->
      <nav class="nav-link">

        <ul>
          <li v-for="(link,i) in links" :key="i" class="nav-item">
            <a class="active" href="#">{{link.text}}</a>
          </li>
        </ul>

      </nav>

    </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      links: [
        {
          text: "Character",
          href: "#"
        },
        {
          text: "Comics",
          href: "#"
        },
        {
          text: "Movies",
          href: "#"
        },
        {
          text: "Tv",
          href: "#"
        },
        {
          text: "Games",
          href: "#"
        },
        {
          text: "Collectibles",
          href: "#"
        },
        {
          text: "Videos",
          href: "#"
        },
        {
          text: "Fans",
          href: "#"
        },
        {
          text: "News",
          href: "#"
        },
        {
          text: "Shop",
          href: "#"
        },
      ]
    }
  }  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >
  .main-header {
    // min-height: 110px;

    .container{
      display: flex;
      justify-content: space-between;

        .logo{
          align-self: center;
          max-width: 85px;
          min-width:85px;
        }
        .nav-link{
          display: flex;
          align-self: center;
          gap: 25px;

           ul{
             display:contents;
           }
           .nav-item{
              min-height: 110px;
              text-transform: uppercase;
              
              font-size: 18px;

             a{
               display:flex;
               height:100%;
               align-items: center;
             }

             a:hover{
                border-bottom: 4px solid #0282F9;
                border-top: 4px solid transparent;
             }
           }
        }  
      }

  }
 
</style>