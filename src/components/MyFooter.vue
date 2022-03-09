<template>
  <div class="main-footer">
        <section class="head-footer">
            <div class="container">
                ciao
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
    min-height: 300px;
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
