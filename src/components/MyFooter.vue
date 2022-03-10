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

        <section class="footer-social">
            <div class="container">
                <button>sign-up</button>

                <div class="link-social">
                    
                    <span>follow us</span>
                    <ul>
                        <li>social</li>
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
    background: url("../assets/img/footer-bg.jpg");
    // min-height: 300px;
    padding:20px 0px;
        
        .container{
            display: flex;

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
    .footer-social {
        // display: flex;
        background-color: #303030;
    }

    .link-social {
        background-color: #303030;
        display: flex;
    }
}
</style>
