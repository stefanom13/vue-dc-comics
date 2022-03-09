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
          <li class="nav-item">
            <a href="#">caratteri</a>
          </li>
        </ul>
        
      </nav>

    </div>
  </div>
</template>

<script>
export default {
  name: 'MyHeader',
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >
  .main-header {
    // min-height: 110px;

    .container{
      display: flex;
      justify-content: space-between;
      min-height: 110px;

        .logo{
          align-self: center;
          width:85px;
        }
        .nav-link{
          display: flex;
          align-self: center;
          gap: 25px;

           ul{
             display:contents;
           }
        }
        
    }



  }
 
</style>