<template>
    <div class="error-page">
        <main>
            <section class="cover-section">
                <div>
                    <h1 class="fluid-gradient-heading text-align-center m-0 heading-type-bold fade-in__gradient">404</h1>
                    <div class="">
                        <span class="contact-welcome text-align-center fade-in">Yeahhh, let's go home and try that again.</span>
                        <div class="d-flex" style="flex-direction:column; animation: 0.8s ease 0.5s 1 normal backwards running fadeIn;">
                            <router-link class="btn-works text-align-center m-auto" to="/" style="border-radius: 4px;">
                                <span>
                                    <span class="btn-works__text">Take me Home</span>
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
                            </router-link>
                            <router-link to="/terms#siteMap" class="text-align-center text-link" >View Site map</router-link>
                        </div>
                        <!-- <a href="index.html" class="btn-works text-align-center" style="display: block;"></a> -->
                    </div>
                </div>
            </section>
        </main>
    </div>
</template>

<script>
export default {
  name: '404'
}
</script>
