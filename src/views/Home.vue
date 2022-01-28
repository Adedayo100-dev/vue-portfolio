<template>
  <div class="home">
    <main>
        <section class="first-section">
            <div class="first-section-content">
                <div class="jumbotron">
                    <h1 class="heading-type-1 fluid-gradient-heading fade-in__gradient"><span>DEE - WHY</span><span>Dee - Why</span></h1>
                    <p class="desc fade-in" lang="en">I'm a front-end web developer. I design vogue websites with aesthetic designs that turn visitors into engaged clients. Let build your brand together...</p>
                    <div class="cta-box">
                        <a href="projects.html" hreflang="en-US" class="btn-cv border-color-white" role="button">
                                View My Works
                            <span class="btn-inline-arrow" tabindex="0" role="button">
                                <svg class="icon icon-arrow-right" id="icon-arrow-right" viewBox="0 0 32 32">
                                    <path d="M30.2 16c0-0.2 0-0.4 0-0.4 0-0.2-0.2-0.2-0.2-0.4l-7.2-7.2c-0.6-0.6-1.2-0.6-1.6 0s-0.6 1.2 0 1.6l5 5.2h-23.2c-0.4 0-0.8 0.2-1 0.4s-0.2 0.4-0.2 0.8c0 0.4 0.2 0.6 0.4 0.8s0.6 0.4 0.8 0.4h23.2l-5 5.2c-0.6 0.6-0.6 1.2 0 1.6 0.6 0.6 1.2 0.6 1.6 0l7.2-7.2c0.2 0 0.2-0.2 0.2-0.4 0 0 0-0.2 0-0.4z"></path>
                                </svg>
                            </span>
                        </a>
                        <!-- <a href="" hreflang="en-US" class="btn-works border-color skewed-glass btn-animate-1" role="button">
                            Contact Me
                            <span class="btn-inline-arrow" tabindex="0" role="button">
                                <svg class="icon icon-arrow-right" id="icon-arrow-right" viewBox="0 0 32 32">
                                    <path d="M30.2 16c0-0.2 0-0.4 0-0.4 0-0.2-0.2-0.2-0.2-0.4l-7.2-7.2c-0.6-0.6-1.2-0.6-1.6 0s-0.6 1.2 0 1.6l5 5.2h-23.2c-0.4 0-0.8 0.2-1 0.4s-0.2 0.4-0.2 0.8c0 0.4 0.2 0.6 0.4 0.8s0.6 0.4 0.8 0.4h23.2l-5 5.2c-0.6 0.6-0.6 1.2 0 1.6 0.6 0.6 1.2 0.6 1.6 0l7.2-7.2c0.2 0 0.2-0.2 0.2-0.4 0 0 0-0.2 0-0.4z"></path>
                                </svg>
                            </span>
                        </a> -->
                        <a href="contact.html" hreflang="en-US" class="btn-works" role="button">
                            <span>
                                <span class="btn-works__text">Start a Project</span>
                                <span class="btn-works__icon">
                                    <span class="btn-works__icon__main">
                                        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M1 11L10.5 1.5" stroke="#333333"></path> <path d="M4 1H11V8" stroke="#333333"></path>
                                        </svg>
                                    </span>
                                    <span class="btn-works__icon__secondary">
                                        <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M1 11L10.5 1.5" stroke="#333333"></path>
                                            <path d="M4 1H11V8" stroke="#333333"></path>
                                        </svg>
                                    </span>
                                </span>
                            </span>
                        </a>
                    </div>
                    <span claas="theme-mode" onclick="changeTheme()">✺ Light Mode</span>
                </div>
                <div class="arrow-container">
                    <span class="arrow prev-arrow btn-animate" tabindex="0" role="button" aria-label="Previous slide">
                        <svg class="icon icon-arrow-left" id="icon-arrow-left" viewBox="0 0 32 32">
                            <path d="M1.8 16c0 0.2 0 0.2 0 0.4s0.2 0.4 0.2 0.4l7.2 7.2c0.6 0.6 1.2 0.6 1.6 0s0.6-1.2 0-1.6l-5-5.2h23.2c0.4 0 0.6-0.2 0.8-0.4s0.4-0.6 0.4-0.8c0-0.4-0.2-0.6-0.4-0.8s-0.6-0.4-0.8-0.4h-23.2l5-5.2c0.6-0.6 0.6-1.2 0-1.6-0.4-0.6-1-0.6-1.6 0l-7.2 7.2c0 0-0.2 0.2-0.2 0.4 0 0 0 0.2 0 0.4z"></path>
                        </svg>
                    </span>
                    <span class="arrow next-arrow btn-animate" tabindex="0" role="button" aria-label="Next slide">
                        <svg class="icon icon-arrow-right" id="icon-arrow-right" viewBox="0 0 32 32">
                            <path d="M30.2 16c0-0.2 0-0.4 0-0.4 0-0.2-0.2-0.2-0.2-0.4l-7.2-7.2c-0.6-0.6-1.2-0.6-1.6 0s-0.6 1.2 0 1.6l5 5.2h-23.2c-0.4 0-0.8 0.2-1 0.4s-0.2 0.4-0.2 0.8c0 0.4 0.2 0.6 0.4 0.8s0.6 0.4 0.8 0.4h23.2l-5 5.2c-0.6 0.6-0.6 1.2 0 1.6 0.6 0.6 1.2 0.6 1.6 0l7.2-7.2c0.2 0 0.2-0.2 0.2-0.4 0 0 0-0.2 0-0.4z"></path>
                        </svg>
                    </span>
                </div>
            </div>
        </section>

        <section class="second-section" itemscope itemtype="https://schema.org/Person">
            <div class="second-section-content">
                <!-- <div>
                    <img itemprop="image" src="images/me.jpg" alt="" width="100%">
                </div> -->
                <div class="tile-content">
                    <img itemprop="image" src="../assets/images/me.jpg" alt="Taiwo Adedayo Emmanuel(Dee-Why)" width="100%">
                    <div class="tile-border">
                        <span class="border-vertical-grid-left"></span>
                        <span class="border-vertical-grid-right"></span>
                        <span class="plus-graphic border-plus-graphic-tr"></span>
                        <span class="plus-graphic border-plus-graphic-bl"></span>
                    </div>
                </div>

                <meta itemprop="name" content="Taiwo Adedayo Emmanuel"/>
                <meta itemprop="birthDate" content="2002-11-13"/>
                <div>
                    <div class="lg-mt-0">
                        <h3 class="first-h3 outline-text">What I Do</h3>
                    </div>
                    <div class="wid-content" itemprop="about">
                        <p>Hello, I'm <del>T&aacute;iw&ograve; &Aacute;d&eacute;d&aacute;y&#7885; aka</del> Dee-Why. I'm a web developer based in <span itemprop="nationality">Canada</span>. I'm focused on crafting bespoke, fast & responsive websites with user friendly experiences that accurately reflects you and your brand.</p>
                        <p>I help businesses do better online with scalable, optimised, maintainable, accessible websites. I typically invest in new business ideas with large knowledge content. Take my talent and experience. Let's make development sound.</p>
                    </div>
                    <div class="subtitle-right">
                        <span class="read-more"><a href="about.html#about-content">Read More <span>&rarr;</span></a></span>
                    </div>
                </div>
            </div>
        </section>

        <section class="third-section">
            <div class="third-section-content">
                <div>
                    <h3 class="outline-text">Showcase</h3>
                </div>
                <div class="works-list">
                    <ul class="custom-scroll">
                        <li>
                            <div>
                                <img src="images/images (5).jpeg" alt="">
                                <!-- <img src="images/images (5i).jpeg" alt=""> -->
                            </div>
                            <div class="border-color">
                                <h6>Minimalist Web-Designs</h6>
                                <p>A collection of some minimalist website projects I've made. Consecteur goto inter millian der hat tunnel app</p>
                                <div class="d-flex">
                                    <a href="projects.html" class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div>
                                <img src="images/images (5).jpeg" alt="">
                            </div>
                            <div class="border-color">
                                <h6>Javascript Projects</h6>
                                <p>My collection of javascript applications</p>
                                <div class="d-flex">
                                    <a href="projects.html" class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div>
                                <img src="images/images - 2021-07-17T043609.996.jpeg" alt="">
                            </div>
                            <div class="border-color">
                                <h6>Portfolio Design</h6>
                                <p>Lorem ipsum dolor sit amet consecteur goto inter millian der hat tunnel app</p>
                                <div class="d-flex">
                                    <a href="projects.html" class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div>
                                <img src="images/images - 2021-07-17T043609.996.jpeg" alt="">
                            </div>
                            <div class="border-color">
                                <h6>E-commerce Websites</h6>
                                <p>Lorem ipsum dolor sit amet consecteur goto inter millian der hat tunnel app</p>
                                <div class="d-flex">
                                    <a href="projects.html" class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div>
                                <img src="images/images - 2021-07-17T043103.934.jpeg" alt="">
                            </div>
                            <div class="border-color">
                                <h6>Website Clones</h6>
                                <p>Lorem ipsum dolor sit amet consecteur goto inter millian der hat tunnel app</p>
                                <div class="d-flex">
                                    <a href="projects.html" class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li>
                        <!-- <li>
                            <img src="" alt="">
                            <div class="border-color">
                                <h6>WordPress Sites</h6>
                                <p>Lorem ipsum dolor sit amet consecteur goto inter millian der hat tunnel app</p>
                                <div class="d-flex">
                                    <a href="projects.html"class="skewed-glass btn-hv-animate-1 ml-auto">Check Out</a>
                                </div>
                            </div>
                        </li> -->
                    </ul>
                </div>
                <div>
                    <div class="works-list-arrows">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" class="wg-arow-left" stroke-linecap="round" stroke-linejoin="round" points="30 7.5 22.5 15 30 22.5"></polyline>
                            </g>
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" class="wg-arow-right" stroke-linecap="round" stroke-linejoin="round" points="22.5 7.5 30 15 22.5 22.5"></polyline>
                            </g>
                        </svg>
                    </div>
                </div>
            </div>
            <div class="spiral" style="position: absolute; bottom: 0; left: -71px; overflow: visible; z-index: 0;">
                <div class="spiral-arrow">
                    <a href="about.html">
                        <svg viewBox="0 0 49 48" fill="none" xmlns="http://www.w3.org/2000/svg" class="spiral-arrow-svg">
                            <path d="M32.844 21.9998L22.116 11.2718L24.944 8.44385L40.5 23.9998L24.944 39.5558L22.116 36.7278L32.844 25.9998H8.5V21.9998H32.844Z" fill="none"></path>
                        </svg>
                    </a>
                </div>
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 500 500" class="spiral-svg">
                    <defs>
                        <path d="M50,250c0-110.5,89.5-200,200-200s200,89.5,200,200s-89.5,200-200,200S50,360.5,50,250" id="textcircle"></path>
                    </defs>
                    <text dy="-10" textLength="1220">
                        <textPath xlink:href="#textcircle" class="spiral-textpath">
                    Dee - Why's Collections•Dee - Why's Collections •
                        </textPath>
                    </text>
                </svg>
            </div>
        </section>

        <section class="fourth-section">
            <div class="fourth-section-content" id="brag">
                <div class="">
                    <h3 class="outline-text">Features</h3>
                </div>
                <div class="config-box">
                    <div class="config-item" id="yearsOfExperience">
                        <div class="text-align-center">
                            <span class="config-value fluid-gradient-heading">3<span class="config-sub"> years</span></span>
                            Experience
                        </div>
                    </div>
                    <div class="config-item">
                        <div class="text-align-center">
                            <span class="config-value fluid-gradient-heading">4<sup>+</sup></span>
                            Lightening Fast
                        </div>
                    </div>
                    <div class="config-item">
                        <div class="text-align-center">
                            <span class="config-value fluid-gradient-heading">6</span>
                            Breakpoints
                        </div>
                    </div>
                    <div class="config-item">
                        <div class="text-align-center">
                            <span class="config-value fluid-gradient-heading">100<span class="config-sub">%</span></span>
                            Passion
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="fifth-section">
            <div class="fifth-section-content">
                <!-- Testimonies -->
                <div>
                    <h3 class="outline-text">Client's</h3>
                    <h3 class="outline-text">Testimonials</h3>
                </div>
                <div class="testimonials">
                    <ul class="scroller custom-scroll">
                        <li class="testimonial-card">
                            <img src="images/me.jpg" class="avatar" alt="Elise" width="50px">
                            <div class="testimonial-content">
                                <p>
                                    "Dee - Why is a trust-worthy business partner. Working with him is nostrud imperdiet abhorreant qui, hinc incorrupte vix ad. Vel id aliquip oblique. Primis feugait sit an, brute illud convenire duo ea"
                                </p>
                                <span>@_elise</span>
                            </div>
                        </li>
                        <li class="testimonial-card">
                            <img src="images/me.jpg" class="avatar" alt="Elise" width="50px">
                            <div class="testimonial-content">
                                <p>
                                    "Vitae pericula maluisset ut mei, pro eleifend gubergren eu. Et his brute graeci. Affert ponderum ei vel, dolorum accumsan ea has. Sea oblique salutatus ei, simul lucilius pri et"
                                </p>
                                <span>@_john</span>
                            </div>
                        </li>
                        <li class="testimonial-card">
                            <img src="images/me.jpg" class="avatar" alt="Elise" width="50px">
                            <div class="testimonial-content">
                                <p>
                                    "Ne est virtute indoctum, quaeque vituperata cam ut. Te nisl quaeque pri. Vix ex autem latine, mel ne nobis scaevola, ei est dolor utinam commune. Pri unum doctus in, cu primis pertinax eos"
                                </p>
                                <span>@imani_</span>
                            </div>
                        </li>
                        <li class="testimonial-card">
                            <img src="images/me.jpg" class="avatar" alt="Elise" width="50px">
                            <div class="testimonial-content">
                                <p>
                                    "Ne est virtute indoctum, quaeque vituperata cam ut. Te nisl quaeque pri. Vix ex autem latine, mel ne nobis scaevola, ei est dolor utinam commune. Pri unum doctus in, cu primis pertinax eos"
                                </p>
                                <span>@_pet_er_</span>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="test-arrows-2">
                    <span class="test-counter">1/4</span>
                    <div class="">
                        <span class="test-prev">
                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                                <g fill="none" fill-rule="evenodd">
                                    <rect width="30" height="30"></rect>
                                    <polyline stroke="#FFF" class="wg-arow-left" stroke-linecap="round" stroke-linejoin="round" points="30 7.5 22.5 15 30 22.5"></polyline>
                                </g>
                            </svg>
                        </span>
                        <span class="test-next">
                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                                <g fill="none" fill-rule="evenodd">
                                    <rect width="30" height="30"></rect>
                                    <polyline stroke="#FFF" class="wg-arow-right" stroke-linecap="round" stroke-linejoin="round" points="22.5 7.5 30 15 22.5 22.5"></polyline>
                                </g>
                            </svg>
                        </span>
                    </div>
                </div>
            </div>
        </section>
         <div class="accordion">
            <details>
                <summary>
                    <h5>What I can do for you</h5>

                    <div class="accordion-flush">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" points="7.5 11.25 15 18.75 22.5 11.25"></polyline>
                            </g>
                        </svg>
                    </div>
                </summary>
                <div class="acc">
                    <p>I can help you build your:</p>
                    <ul>
                        <li>
                            <a href="contact.html">Professional Portfolio</a>
                        </li>
                        <li>
                            <a href="contact.html">E-commerce website</a>
                        </li>
                        <li>
                            <a href="contact.html">Revamp your website</a>
                        </li>
                        <li>
                            <a href="contact.html">Let collaborate</a>
                        </li>
                    </ul>
                </div>
            </details>
            <details>
                <summary>
                    <h5>How long will it take to revamp our website?</h5>
                    <div class="accordion-flush">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" points="7.5 11.25 15 18.75 22.5 11.25"></polyline>
                            </g>
                        </svg>
                    </div>
                </summary>
                <div class="acc">
                    <p>Most projects do take up to 30 days &PlusMinus; 1 week to complete. You can request for a fast track delivery with this link &#8658; <a href="pricing.html">Click Me!</a></p>
                </div>
            </details>
            <details>
                <summary>
                    <h5>Do you have any suggestions?</h5>
                    <div class="accordion-flush">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" points="7.5 11.25 15 18.75 22.5 11.25"></polyline>
                            </g>
                        </svg>
                    </div>
                </summary>
                <div class="acc">
                    <form class="textarea-container">
                        <textarea name="" id="" cols="30" rows="10" placeholder="Comments."></textarea>
                        <input type="submit" class="accordion-submit textarea-submit" value="Let Me Know">
                    </form>
                </div>
            </details>
            <details>
                <summary>
                    <h5>FAQs</h5>
                    <div class="accordion-flush">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                            <g fill="none" fill-rule="evenodd">
                                <rect width="30" height="30"></rect>
                                <polyline stroke="#FFF" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" points="7.5 11.25 15 18.75 22.5 11.25"></polyline>
                            </g>
                        </svg>
                    </div>
                </summary>
                <div class="acc">
                    <ul>
                        <li>
                          <router-link to="/pricing">How much does a project cost?</router-link>
                        </li>
                        <li>
                          <router-link to="/#brag">How many years of experience do you have?</router-link>
                        </li>
                        <li>
                          <router-link to="/" data-answer="yes">Do you work internationally?</router-link>
                        </li>
                        <li>
                          <router-link to="/contact">How do I contact you?</router-link>
                        </li>
                        <li>
                            <form class="input-container d-flex" action="mailto:adedayoemmanuelt@gmail.com" >
                                <input type="text" name="" id="" placeholder="Ask...">
                                <input type="submit" class="accordion-submit input-submit" value="Submit">
                            </form>
                        </li>
                    </ul>
                </div>
            </details>
        </div>
       <div class="first-bond">
            <div class="name-scroll">
                <div>
                    Taiwo <span>Adedayo </span>Taiwo <span>
                    Adedayo </span>Taiwo <span>Adedayo </span>
                    Taiwo <span>Adedayo </span>
                </div>
                <div>
                    Taiwo <span>Adedayo </span>Taiwo <span>
                    Adedayo </span>Taiwo <span>Adedayo </span>
                    Taiwo <span>Adedayo </span>
                </div>
            </div>
        </div>

        <!-- <div class="location-container">
            <div>
                <img src="images/location-2.svg" class="dark-theme-loc location-icon m-auto" height="17px" >
                <img src="images/location-3.svg" class="light-theme-loc location-icon m-auto" height="17px">
                <span>Lagos, Nigeria</span>
            </div>
        </div>

        <footer>
            <span>&copy;<span itemprop="copyrightYear"> 2021</span> Taiwo Adedayo. All Rights Reserved.</span>
        </footer> -->
        <Footer/>
    </main>
  </div>

</template>

<style scoped>
    .spiral{
        position: relative;
        width: 207px;
    }
    .spiral-arrow{
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%,-50%);
    }
    .spiral-arrow-svg {
        width: 100px;
        max-width: 40px;
    }
    .spiral-arrow-svg path {
        fill: #FFF;
    }
    .spiral-svg{
        width: 100%;
        animation: rotate-spiral 30s linear infinite;
    }
    .spiral-textpath{
        font-size: 37.5px;
        /* font-family: "Grotesk"; */
        text-transform: uppercase;
        letter-spacing: -9px;
        fill: rgba(128, 128, 128, 0.5);
    }
    @keyframes rotate-spiral {
        100% {
            transform: rotate(1turn);
        }
    }
</style>

<script>
// @ is an alias to /src
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Footer
  }
}
</script>
