<script setup>
const imageShape = '/assets/images/image-shape.svg';
const imageShape2 = '/assets/images/header-shape-2.svg';
const header = {
    logo: "assets/images/logo.png",
    headerTitle: "<span>POS Management System</span> For your business solution",
    headerText: "Please, purchase our pos management system and get support for 24 hours in 7 days.",
    img: "assets/images/header-app.png"
}
// expression condition
const responsive = false
// class binding
const textDanger = "text-danger"
const textGreen = "text-success"
// style binding
const marginLeft = "margin-left:30px"

</script>
<template>
    <header class="header-area">
        <div class="navbar-area">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <nav class="navbar navbar-expand-lg">
                            <a class="navbar-brand" href="#home">
                                <img :src="header.logo" alt="Logo">
                            </a>
                            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                                <span class="toggler-icon"></span>
                                <span class="toggler-icon"></span>
                                <span class="toggler-icon"></span>
                            </button>

                            <div class="collapse navbar-collapse sub-menu-bar" id="navbarSupportedContent">
                                <ul id="nav" class="navbar-nav " :style="marginLeft">
                                    <li class="nav-item active">
                                        <a class="page-scroll" href="#home">Home</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="page-scroll" href="#advantage">Advantage</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="page-scroll" href="#features">Features</a>
                                    </li>
                                    
                                    <li class="nav-item">
                                        <a class="page-scroll" href="#pricing">Pricing</a>
                                    </li>
                                    
                                    <li class="nav-item">
                                        <a class="page-scroll" href="#download">Download</a>
                                    </li>
                                    
                                </ul>
                                <ul id="nav-right" class="navbar-nav ml-auto">
                                    
                                    <li class="nav-item">
                                        <a class="sing-in" href="#">Sign in</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="register" href="#">Register</a>
                                    </li>
                                </ul>
                            </div> <!-- navbar collapse -->
                        </nav> <!-- navbar -->
                    </div>
                </div> <!-- row -->
            </div> <!-- container -->
        </div> <!-- navbar area -->

        <div id="home" class="header-hero bg_cover d-lg-flex align-items-center">
            
            <div class="shape shape-1"></div>
            <div class="shape shape-2"></div>
            <div class="shape shape-3"></div>
            <div class="shape shape-4"></div>
            <div class="shape shape-5"></div>
            <div class="shape shape-6"></div>
            
            <div class="container">
                <div class="row align-items-center justify-content-center justify-content-lg-between">
                    <div class="col-lg-6 col-md-10">
                        <div class="header-hero-content">
                            <h3 class="header-title wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.2s" v-html="header.headerTitle"></h3>
                            <p class="text wow fadeInLeftBig" :class="[responsive==true?textGreen:textDanger]" data-wow-duration="1.3s" data-wow-delay="0.6s">{{ header.headerText }}</p>
                            <ul class="d-flex">
                                <li>
                                    <a href="#features" 
                                    rel="nofollow" class="wow fadeInLeftBig btn btn-primary" 
                                    data-wow-duration="1.3s" data-wow-delay="0.8s">See Features</a>
                                </li>

                                <li class="ml-2">
                                    <a href="#pricing" 
                                    rel="nofollow" class="wow fadeInLeftBig btn btn-outline-primary" 
                                    data-wow-duration="1.3s" data-wow-delay="0.8s">Pricing</a>
                                </li>
                            </ul>
                        </div> <!-- header hero content -->
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-6 col-10">
                        <div class="header-image">
                            <img :src="header.img" alt="app" 
                                class="image wow fadeInRightBig" 
                                data-wow-duration="1.3s" 
                                data-wow-delay="0.5s">
                            <div class="image-shape wow fadeInRightBig" 
                                data-wow-duration="1.3s" 
                                data-wow-delay="0.8s">
                                <img :src="imageShape" alt="shape">
                            </div>
                        </div> <!-- header image -->
                    </div>
                </div> <!-- row -->
            </div> <!-- container -->
            <div class="header-shape-1"></div> <!-- header shape -->
            <div class="header-shape-2">
                <img :src="imageShape2" alt="shape">
            </div> <!-- header shape -->
        </div> <!-- header hero -->
    </header>
</template>