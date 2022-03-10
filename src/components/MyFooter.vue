<template>
  <div class="main-footer">
        <section class="head-footer">
            <div class="container">

                <!-- first col -->
                <div class="col">
                    <div class="widget">
                        <h3 class="titleWidget">Dc Comics</h3>
                        <ul class="list_widget">
                          <li>Character</li>
                          <li>Comics</li>
                          <li>Movies</li>
                          <li>Tv</li>
                          <li>Games</li>
                          <li>Videos</li>
                          <li>News</li>
                        </ul>
                    </div>
                    <div class="widget">
                        <h3 class="titleWidget">Shop</h3>
                        <ul class="list_widget">
                          <li>Shop DC</li>
                          <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <!-- second col -->
                <div class="col">

                    <div class="widget">
                        <h3 class="titleWidget">DC</h3>
                        <ul class="list_widget">
                          <li>Terms of Use</li>
                          <li>Privacy policy(new)</li>
                          <li>Ad Choices</li>
                          <li>Advertising</li>
                          <li>Jobs</li>
                          <li>Subscriptions</li>
                          <li>Talent Workshops</li>
                          <li>CPCS Certificates</li>
                          <li>Ratings</li>
                          <li>Shop Help</li>
                          <li>Contact Us</li>
                        </ul>
                    </div>

                </div>
                <!-- third col -->
                <div class="col">

                    <div class="widget">
                        <h3 class="titleWidget">Sites</h3>
                        <ul class="list_widget">
                          <li>DC</li>
                          <li>MAD Magazine</li>
                          <li>DC Kids</li>
                          <li>Universe</li>
                          <li>DC Power Visa</li>
                        </ul>
                    </div>

                </div>

            </div>
        </section>

        <!-- footer social   -->
        <section class="footer-social">
            <div class="container">
                <button  class="butSign-up"><a href="#">Sign-up Now!</a></button>

                <div class="link-social">
                    
                    <span class="F-us">follow us</span>
                  
                    <ul class="wrapSocial">

                        <li>
                            <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                        </li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                        </li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                        </li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                        </li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                        </li>

                    </ul>
                    

                </div>
            </div>
        </section>
  </div>
</template>

<script>
export default {
  name: "MyFooter",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.main-footer {
  color: white;

  .head-footer {
    background:url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;        
        .container{
            display: flex;
            background: url("../assets/img/dc-logo-bg.png");
            background-repeat: no-repeat;
            background-position: right center;
            padding:20px 0px;

            .col{
                width: calc(100% / 9);

                    .list_widget{
                        color: #959595;

                            li{
                                cursor: pointer;
                            }
                    }
               
                
            }
        }
    }

    // <!-- footer social   -->
    .footer-social {
        padding:20px 0;
        background-color: #303030;
      

        .container{
            display: flex;
            align-items: center;
            justify-content:space-between;

            .butSign-up{
                padding:8px;
                color:white;
                background-color:#303030;
                border:2px solid #0282F9;
                text-transform: uppercase;
                font-size:22px;
            }
        }
    }

    .link-social {
        background-color: #303030;
        display: flex;
        align-items: center;
        gap:25px;

            .F-us{
                color: #0282F9;
                text-transform: uppercase;
                font-size:22px;

            }
            .wrapSocial{
                display: flex;
                align-items: center;
                gap:15px;

                li{
                    width:30px;
                }
            }
            
    }
}
</style>
