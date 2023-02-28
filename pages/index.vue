<template>
 <main class="listingPage">
    <div class="container-fluid">
        <div class="row">
            <div class="col-xl-2 col-lg-3 md-4 col-sm-4">
              <!-- sidebar -->
            </div>
            <div class="col-xl-10 col-lg-8 md-8 col-sm-8">
              <!-- content -->
              <FeaturedProduct />
              <div class="mainResults">
                <ul class="s-result-item celwidget">
                  <div class="s-item-container">
                    <div class="a-spacing-micro">
                      <div class="bestSeller">
                        <a href="#">Best Seller</a>
                      </div>
                    </div>
                    <div>
                      <div class="row">
                        <!-- image -->
                        <div class="col-sm-3 text-center">
                          <a href="#">
                            <img src="/img/amazonImg.jpg" style="width:150px" class="img-fluid" />
                          </a>
                        </div>
                        <div class="col-sm-9">
                           <div class="a-row a-spacing-small">
                            <!-- date -->
                            <a href="#">
                              <h2 class="a-size-medium">
                                Harry potter
                                <span class="a-letter-space"></span>
                                <span class="a-letter-space"></span>
                                <span class="a-size-small a-color-secondary"> Sept 5, 2022</span>
                              </h2>
                            </a>
                           </div>

                           <!-- Author -->
                            <div class="a-row a-spacing-small">
                                  <span class="a-size-small a-color-secondary"> by</span>
                                  <span class="a-size-small a-color-secondary"> 
                                    <a href="#" class="a-link-normal a-text-normal"> walter isaacson</a>
                                  </span>                         
                             </div>

                             <!-- shipment -->
                             <div class="a-row">
                              <span class="a-size-small"> Ships to USA</span>
                             </div>

                             <div class="row">
                              <div class="col-sm-7">
                                <div class="a-row a-spacing-none">
                                  <a href="#" class="a-link-normal a-text-normal">Hardcover</a>
                                </div>

                                <!-- Price -->
                                <div class="a-row a-spacing-none">
                                    <a href="#" class="a-link-normal a-text-normal">
                                      <span class="a-offscreen">$89</span>
                                      <span class="a-color-base sx-zero-spacing">
                                        <span class="sx-price sx-price-large">
                                          <sup class="sx-price-currency">$</sup>
                                          <span class="sx-price-whole">99</span>
                                          <sup class="sx-price-fractional">00</sup>
                                        </span>
                                      </span>
                                    </a>
                                    <span class="a-letter-space"></span>
                                    <span class="a-size-base-plus a-color-secondary a-text-strike">$35.99</span>
                                  </div>

                                  <!-- audible trial -->
                                  <div class="a-row a-spacing-none">
                                    <span class="a-size-small a-color-secondary">
                                      Free with audible trial
                                    </span>
                                  </div>
                                  <hr />

                                  <!-- other formats -->
                                  <span class="a-size-small a-color-secondary">
                                    Other formats:
                                    <span class="a-letter-space"></span>
                                    <a href="#" class="a-size-small a-link-normal a-text-normal">
                                      Audio CD
                                    </a>
                                  </span>
                              </div>

                              <!-- ratings -->
                              <div class="col-sm-5">
                                <div class="a-row a-spacing-mini">
                                  <!-- star ratings -->
                                </div>
                              </div>
                             </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </ul>
              </div>
            </div>
        </div>
    </div>
 </main>
</template>

<script>
import FeaturedProduct from '~/components/FeaturedProduct.vue';

export default {
    name: "IndexPage",
    components: { FeaturedProduct }
}
</script>
