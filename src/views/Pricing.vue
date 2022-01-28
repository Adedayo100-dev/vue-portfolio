<template>
    <div class="pricing">
        <main>
            <section class="wks-section-1">
                <h1 class="heading-type-2 fluid-gradient-heading">Pricing</h1>
            </section>
            <div class="px-auto text pricing__welcome-container">
                <span class="contact-welcome">Select one of the following plans</span>
            </div>
            <div class=" wks-section-2">
                <ul class="pricing-list">
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">Basic</h5>
                        <h6><sup>$</sup>600</h6>
                        <ul class="">
                            <li>Static Pages</li>
                            <li>15 GB of storage</li>
                            <li>Phone and email support</li>
                            <li>Help center access</li>
                        </ul>
                        <button class="w-100">PURCHASE</button>
                    </li>
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">Standard</h5>
                        <h6><sup>$</sup>1000</h6>
                        <ul class="">
                            <li>
                                <!-- <svg aria-hidden="true" focusable="false" class="udlite-icon udlite-icon-xsmall udlite-icon-color-neutral udlite-block-list-item-icon">
                                    <use xlink:href="#icon-tick"></use>
                                </svg> -->
                                All the goodness of Basic
                            </li>
                            <li>30 users included</li>
                            <li>15 GB of storage</li>
                            <li>Phone and email support</li>
                            <li>Help center access</li>
                        </ul>
                        <button class="w-100">PURCHASE</button>
                    </li>
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">Premium</h5>
                        <h6><sup>$</sup>1200</h6>
                        <ul class="">
                            <li>30 users included</li>
                            <li>15 GB of storage</li>
                            <li>Phone and email support</li>
                            <li>Help center access</li>
                        </ul>
                        <button class="w-100">PURCHASE</button>
                    </li>
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">WordPress</h5>
                        <h6><sup>$</sup>1000</h6>
                        <ul class="">
                            <li>30 users included</li>
                            <li>15 GB of storage</li>
                            <li>Phone and email support</li>
                            <li>Help center access</li>
                        </ul>
                        <button class="w-100">PURCHASE</button>
                    </li>
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">WordPress</h5>
                        <h6><sup>$</sup>1200</h6>
                        <ul class="">
                            <li>30 users included</li>
                            <li>15 GB of storage</li>
                            <li>Phone and email support</li>
                            <li>Help center access</li>
                        </ul>
                        <button class="w-100">PURCHASE</button>
                    </li>
                    <li class="pricing-item">
                        <h5 class="fluid-gradient-heading">Extra</h5>
                        <ul class="">
                            <li class="list-split">30 users included <input type="checkbox" name="" id="" checked></li>
                            <li class="list-split">15 GB of storage <input type="checkbox" name="" id="" checked></li>
                            <li class="list-split">Phone and email support <input type="checkbox" name="" id="" checked></li>
                            <li class="list-split">Help center access <input type="checkbox" name="" id="" checked></li>
                        </ul>
                        <button class="w-100">ADD</button>

                    </li>

                </ul>
            </div>

            <Footer/>
        </main>
    </div>
</template>

<script>
import Footer from '@/components/Footer.vue'
export default {
  name: 'Pricing',
  components: {
    Footer
  }
}
</script>
