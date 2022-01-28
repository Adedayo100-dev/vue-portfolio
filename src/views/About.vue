<template>
  <div class="about">
    <main itemscope itemtype="https://schema.org/AboutPage">
        <section class="wks-section-1">
            <h1 class="heading-type-2 fluid-gradient-heading">About</h1>
        </section>
        <section class="wks-section-2" style="overflow-x: hidden;" itemprop="mainContentOfPage">
            <div>
                <img itemprop="primaryImageOfPage" src="../assets/me.jpg" class="d-block about-image" alt="Taiwo Adedayo pic" usemap="#me">
            </div>
                  <!-- <map name="me">
                    <area shape="rect" coords="0,0,0,0" alt="Taiwo Adedayo">
                 </map>  -->
                 <!-- <figcaption> Adedayo Taiwo </figcaption> <a href="#"></a> -->
            <div class="sub-section-2 w-100">
                <div class="about-content" itemprop="about">
                    <p>I'm a full-stack web developer focused on crafting bespoke, fast & responsive websites with user friendly experiences that accurately reflects you and your brand.</p>
                    <p>I help businesses do better online with scalable, optimised, maintainable, accessible websites. Esse molestias optio, laboriosam deleniti, saepe quisquam veritatis culpa nisi minus excepturi dolore aliquid? Commodi aliquid at facere quod saepe cumque culpa.</p>
                    <p>I help businesses do better online with scalable, optimised, maintainable, accessible websites. Esse molestias optio, laboriosam deleniti, saepe quisquam veritatis culpa nisi minus excepturi dolore aliquid? Commodi aliquid at facere quod saepe cumque culpa.</p>
                </div>
            </div>
        </section>
        <div class="about-cta-box">
            <button class="about-cta-button">
                <a href="contact.html">Start a Project</a>
            </button>
        </div>
        <Footer/>
    </main>
  </div>
</template>

<script>
import Footer from '@/components/Footer.vue'
export default {
  name: 'About',
  components: {
    Footer
  }
}
</script>
