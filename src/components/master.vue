<script setup>
import headerComponent from '../components/header.vue'
import footerComponent from '../components/footer.vue'

const header = {
    headerTitle: "<span>POS Management System</span> For your business solution",
    headerText: "Please, purchase purchase our pos management system and get support for 24 hours in 7 days.",
    img: "assets/images/header-app.png"
}


const dashboardImg = "assets/images/dashboard.png"
const person = "assets/images/person_1.png"
const downloadShape = "assets/images/download-shape.svg"
const appStore = "assets/images/app-store.png"
const playStore = "assets/images/play-store.png"

// class binding
const itemCenter = "align-items-center"
// style binding
const headerFeature =  "text-align:center"

</script>

<template>  
   
    <div class="preloader">
        <div class="loader">
            <div class="ytp-spinner">
                <div class="ytp-spinner-container">
                    <div class="ytp-spinner-rotator">
                        <div class="ytp-spinner-left">
                            <div class="ytp-spinner-circle"></div>
                        </div>
                        <div class="ytp-spinner-right">
                            <div class="ytp-spinner-circle"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!--====== PRELOADER PART ENDS ======-->
    
    <!--====== HEADER PART START ======-->

    <headerComponent/>

    <!--====== HEADER PART ENDS ======-->   
    
    <!--====== FEATUR PART START ======-->
    
    <section id="features" class="about-area pt-70 pb-120">
        <div class="container">
                <h3 :style="headerFeature">Features</h3>               
            <div class="row" :class="itemCenter"> 
                <div class="col-lg-4">
                    <div class="about-content mt-50 wow fadeInRightBig" 
                        data-wow-duration="1.3s" data-wow-delay="0.5s">
                        <div class="section-title">
                            <span class="caption aos-init aos-animate" 
                                data-aos="fade-up" data-aos-delay="0">Digital Services</span>
                            <h3 class="title pb-3">Selling POS Management System</h3>                            

                            <div class="mb-2 aos-init aos-animate" data-aos="fade-up" data-aos-delay="200">
                                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast</p>
                                <ul class="list-unstyled ul-check primary pt-3">
                                <li>There live the blind texts</li>
                                <li>Far far away behind the word</li>
                                </ul>
                            </div>
                            <div class="mb-4 aos-init aos-animate" data-aos="fade-up" data-aos-delay="300">
                                <div class="untree_co-testimonial d-flex">
                                    <div class="text">
                                        <blockquote>
                                            “Separated they <span class="highlight">live in Bookmarksgrove right at the coast of the Semantics</span>, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. ”
                                        </blockquote>
                                        <div class="author d-flex">
                                            <div class="pic mr-3">
                                                <img :src="person" alt="Image" class="img-fluid">
                                            </div>
                                            <div>
                                                <strong class="d-block">James Anderson</strong><span class="d-block">Facebook, Product Lead</span>
                                            </div>
                                        </div>
                                    </div>
                                </div> 
                            </div>
                        </div> <!-- section title -->
                       
                    </div> <!-- about content -->
                </div>
                <div class="col-lg-8">
                    <div class="mt-50 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                        <div class="about-shape"></div>
                        <img class="app img-thumbnail rounded" :src="dashboardImg" alt="app">
                    </div> <!-- about image -->
                </div>
            </div> <!-- row -->
        </div> <!-- container -->
    </section>
    
    <!--====== FEATUR PART ENDS ======-->
    

    <div class="untree_co-section bg-light">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-lg-5 order-lg-2 js-custom-dots">
                    <a href="#" class="service link horizontal d-flex aos-init aos-animate active" data-aos="fade-left" data-aos-delay="0" data-index="1">
                        <div class="service-icon color-1 mb-4">
                        <svg class="bi bi-app-indicator" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" d="M5.5 2A3.5 3.5 0 0 0 2 5.5v5A3.5 3.5 0 0 0 5.5 14h5a3.5 3.5 0 0 0 3.5-3.5V8a.5.5 0 0 1 1 0v2.5a4.5 4.5 0 0 1-4.5 4.5h-5A4.5 4.5 0 0 1 1 10.5v-5A4.5 4.5 0 0 1 5.5 1H8a.5.5 0 0 1 0 1H5.5z"></path>
                        <path d="M16 3a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"></path>
                        </svg>
                        </div> 
                        <div class="service-contents">
                        <h3>Grow Your Business</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                        </div> 
                    </a> 
                    <a href="#" class="service link horizontal d-flex aos-init aos-animate" data-aos="fade-left" data-aos-delay="100" data-index="2">
                        <div class="service-icon color-2 mb-4">
                        <svg class="bi bi-arrow-repeat" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" d="M2.854 7.146a.5.5 0 0 0-.708 0l-2 2a.5.5 0 1 0 .708.708L2.5 8.207l1.646 1.647a.5.5 0 0 0 .708-.708l-2-2zm13-1a.5.5 0 0 0-.708 0L13.5 7.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l2-2a.5.5 0 0 0 0-.708z"></path>
                        <path fill-rule="evenodd" d="M8 3a4.995 4.995 0 0 0-4.192 2.273.5.5 0 0 1-.837-.546A6 6 0 0 1 14 8a.5.5 0 0 1-1.001 0 5 5 0 0 0-5-5zM2.5 7.5A.5.5 0 0 1 3 8a5 5 0 0 0 9.192 2.727.5.5 0 1 1 .837.546A6 6 0 0 1 2 8a.5.5 0 0 1 .501-.5z"></path>
                        </svg>
                        </div> 
                        <div class="service-contents">
                        <h3>Build Products</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                        </div> 
                    </a> 
                    <a href="#" class="service link horizontal d-flex aos-init aos-animate" data-aos="fade-left" data-aos-delay="200" data-index="3">
                        <div class="service-icon color-3 mb-4">
                            <svg class="bi bi-briefcase" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M0 12.5A1.5 1.5 0 0 0 1.5 14h13a1.5 1.5 0 0 0 1.5-1.5v-6h-1v6a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5v-6H0v6z"></path>
                            <path fill-rule="evenodd" d="M0 4.5A1.5 1.5 0 0 1 1.5 3h13A1.5 1.5 0 0 1 16 4.5v2.384l-7.614 2.03a1.5 1.5 0 0 1-.772 0L0 6.884V4.5zM1.5 4a.5.5 0 0 0-.5.5v1.616l6.871 1.832a.5.5 0 0 0 .258 0L15 6.116V4.5a.5.5 0 0 0-.5-.5h-13zM5 2.5A1.5 1.5 0 0 1 6.5 1h3A1.5 1.5 0 0 1 11 2.5V3h-1v-.5a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5V3H5v-.5z"></path>
                            </svg>
                        </div> 
                        <div class="service-contents">
                            <h3>Success Every Day</h3>
                            <p>
                                Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.
                            </p>
                        </div> 
                    </a> 
                    <a href="#" class="service link horizontal d-flex aos-init aos-animate" data-aos="fade-left" data-aos-delay="300" data-index="4">
                        <div class="service-icon color-4 mb-4">
                            <svg class="bi bi-collection" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M14.5 13.5h-13A.5.5 0 0 1 1 13V6a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-.5.5zm-13 1A1.5 1.5 0 0 1 0 13V6a1.5 1.5 0 0 1 1.5-1.5h13A1.5 1.5 0 0 1 16 6v7a1.5 1.5 0 0 1-1.5 1.5h-13zM2 3a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 0-1h-11A.5.5 0 0 0 2 3zm2-2a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 0-1h-7A.5.5 0 0 0 4 1z"></path>
                            </svg>
                        </div> 
                        <div class="service-contents">
                            <h3>Bring Ideas to Life</h3>
                            <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                        </div> 
                    </a> 
                </div>
                <div class="col-lg-7">
                <div class="img-shadow">
                <div class="owl-single no-dots owl-carousel owl-loaded">             
                
                
                
                <div class="owl-stage-outer owl-height" style="height: 468.172px;"><div class="owl-stage" style="transform: translate3d(-1230px, 0px, 0px); transition: all 0.8s ease 0s; width: 4920px;"><div class="owl-item cloned" style="width: 615px;"><div class="item">
                <span class="number">3/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item cloned" style="width: 615px;"><div class="item">
                <span class="number">4/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item active" style="width: 615px;"><div class="item">
                <span class="number">1/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item" style="width: 615px;"><div class="item">
                <span class="number">2/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item" style="width: 615px;"><div class="item">
                <span class="number">3/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item" style="width: 615px;"><div class="item">
                <span class="number">4/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item cloned" style="width: 615px;"><div class="item">
                <span class="number">1/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div><div class="owl-item cloned" style="width: 615px;"><div class="item">
                <span class="number">2/4</span>
                <img :src="dashboardImg" alt="Image" class="img-fluid">
                </div></div></div></div><div class="owl-nav disabled"><div class="owl-prev"><span class="icon-keyboard_backspace"></span></div><div class="owl-next"><span class="icon-keyboard_backspace"></span></div></div><div class="owl-dots"><div class="owl-dot active"><span></span></div><div class="owl-dot"><span></span></div><div class="owl-dot"><span></span></div><div class="owl-dot"><span></span></div></div></div>
                </div>
                </div> 
            </div> 
        </div> 
    </div>

    
    <!--====== DOWNLOAD PART START ======-->
    
    <section id="download" class="download-area pt-70 pb-40">
        <div class="container">
            <div class="row justify-content-center align-items-center">
                <div class="col-lg-6 col-md-9">
                    <div class="download-image mt-50 wow fadeInRightBig" data-wow-duration="1.3s" data-wow-delay="0.2s">
                        <img class="image" :src="header.img" alt="download">
                        
                        <div class="download-shape-1"></div>
                        <div class="download-shape-2">
                            <img class="svg" :src="downloadShape" alt="shape">
                        </div>
                    </div> <!-- download image -->
                </div>
                <div class="col-lg-6">
                    <div class="download-content mt-45 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                        <h3 class="download-title">Download and Start Using!</h3>
                        <p class="text">Alii nusquam cu duo, vim eu consulatu percipitur, meis doorcomprehen sam at vis. Vel ut dignissim signiferumq Alii nusquam cuduo, vim eusde consulatu percipitur, meis dolor comprehensam at vij. Alii nusquam cu duo, vim eu consulatu percipitur, meis doorcomprehen sam at vis. Vel ut dignissim signiferumq nusquam.</p>
                        <ul>
                            <li>
                                <a class="app-store" href="#">
                                    <img :src="appStore" alt="store">
                                </a>
                            </li>
                            <li>
                                <a class="play-store" href="#">
                                    <img :src="playStore" alt="store">
                                </a>
                            </li>
                        </ul>
                    </div> <!-- download image -->
                </div>
            </div> <!-- row -->
        </div> <!-- container -->
    </section>
    
    <!--====== DOWNLOAD PART ENDS ======-->
    <!--====== SERVICES PART START ======-->
    <section id="advantage" class="services-area pt-110 pb-120">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-7">
                    <div class="section-title text-center pb-25">
                        <h3 class="title">Advantage of POS Management System</h3>
                        <p class="text">Alii nusquam cu duo, vim eu consulatu percipitur, meis dolor comprehensam at vis. Vel ut percipitur dignissim signiferumque.</p>
                    </div> <!-- section title -->
                </div>
            </div> <!-- row -->
            <div class="row">
                <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-1 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s" data-wow-delay="0.2s">
                        <div class="services-icon d-flex align-items-center justify-content-center">
                            <i class="lni lni-layers"></i>
                        </div>
                        <div class="services-content">
                            <h4 class="services-title"><a href="#">Clean Design</a></h4>
                            <p class="text">Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy.</p>
                        </div>
                    </div> <!-- single services -->
                </div>
                <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-2 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s" data-wow-delay="0.4s">
                        <div class="services-icon d-flex align-items-center justify-content-center">
                            <i class="lni lni-layout"></i>
                        </div>
                        <div class="services-content">
                            <h4 class="services-title"><a href="#">Easy to Use</a></h4>
                            <p class="text">Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy.</p>
                        </div>
                    </div> <!-- single services -->
                </div>
                <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-3 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s" data-wow-delay="0.6s">
                        <div class="services-icon d-flex align-items-center justify-content-center">
                            <i class="lni lni-bolt"></i>
                        </div>
                        <div class="services-content">
                            <h4 class="services-title"><a href="#">Fast Loading</a></h4>
                            <p class="text">Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy.</p>
                        </div>
                    </div> <!-- single services -->
                </div>
                <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-4 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s" data-wow-delay="0.8s">
                        <div class="services-icon d-flex align-items-center justify-content-center">
                            <i class="lni lni-protection"></i>
                        </div>
                        <div class="services-content">
                            <h4 class="services-title"><a href="#">All Elements</a></h4>
                            <p class="text">Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy.</p>
                        </div>
                    </div> <!-- single services -->
                </div>
            </div> <!-- row -->
        </div> <!-- container -->
    </section>
    <!--====== SERVICES PART ENDS ======-->
    
    <!--====== Pricing PART START ======-->
    <div class="untree_co-section bg-light" id="pricing">
        <div class="container">
            <div class="row pricing-title">
                <div class="col-12 text-center wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                    <h2 class="heading">Pricing</h2>
                    <p>Pricing for everyone. Choose your plan now!</p>
                </div>
            </div> 
            <div class="row justify-content-center">
                <div class="col-lg-10">
                    <div class="row">
                        <div class="col-lg-4 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                            <div class="pricing">
                                <div class="body">
                                    <div class="price">
                                        <span class="d-block plan">Free</span>
                                        <span class="price"><sup>$</sup><span>0</span></span>
                                    </div>
                                    <ul class="list-unstyled ul-check primary mb-5">
                                        <li>
                                            There live the blind texts
                                        </li>
                                        <li>Far far away behind the word</li>
                                        <li>Far from the countries Vokalia and Consonantia</li>
                                    </ul>
                                    <p class="text-center mb-0"><a href="#" class="btn btn-outline-primary">Get Started</a></p>
                                </div>
                            </div> 
                        </div> 
                        <div class="col-lg-4 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                            <div class="pricing active">
                                <div class="body">
                                    <div class="price">
                                    <span class="d-block plan">Standard</span>
                                    <span class="price"><sup>$</sup><span>19.99</span></span>
                                    </div>
                                <ul class="list-unstyled ul-check primary mb-5">
                                    <li>There live the blind texts</li>
                                    <li>Far far away behind the word</li>
                                    <li>Far from the countries Vokalia and Consonantia</li>
                                </ul>
                                    <p class="text-center mb-0">
                                        <a href="#" class="btn btn-primary">Get Started</a>
                                    </p>
                                </div>
                            </div> 
                        </div> 
                        <div class="col-lg-4 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                            <div class="pricing">
                                <div class="body">
                                    <div class="price">
                                    <span class="d-block plan">Premium</span>
                                    <span class="price"><sup>$</sup><span>79.99</span></span>
                                    </div>
                                    <ul class="list-unstyled ul-check primary mb-5">
                                        <li>There live the blind texts</li>
                                        <li>Far far away behind the word</li>
                                        <li>Far from the countries Vokalia and Consonantia</li>
                                    </ul>
                                    <p class="text-center mb-0">
                                        <a href="#" class="btn btn-outline-primary">Get Started</a>
                                    </p>
                                </div>
                            </div> 
                        </div> 
                    </div> 
                </div> 
            </div> 
        </div> 
    </div>
    <!--====== PRICING PART ENDS ======-->

    <!--====== PART START ======-->
    
    <footerComponent/>
    
    <!--====== PART ENDS ======-->
    
    <!--====== BACK TOP TOP PART START ======-->

    <a href="#" class="back-to-top"><i class="lni lni-chevron-up"></i></a>

    <!--====== BACK TOP TOP PART ENDS ======-->
    
    
</template>