{% extends "base.html" %}
{% load static %}
{% block content %}
<!-- end header -->
<section class="p-0 position-relative wow animate__fadeIn">
    <div class="opacity-medium bg-extra-dark-gray z-index-0"></div>
    <div class="container position-relative">
        <div class="row">
            <div class="col-12 d-flex flex-column justify-content-center text-center one-third-screen page-title-large">
                <!-- start sub title -->
                <span class="d-block text-white-2 opacity6 margin-10px-bottom alt-font">디지털 케어 네트워크</span>
                <!-- end sub title -->
                <!-- start page title -->
                <h1 class="alt-font text-white-2 font-weight-600 w-55 md-w-80 sm-w-100 mx-auto mb-0">연구소 소개</h1>
                <!-- end page title -->
            </div>
            <div class="down-section text-center"><a href="#overline" class="inner-link"><i class="ti-arrow-down icon-extra-small text-white-2 bg-deep-pink padding-15px-all sm-padding-10px-all rounded-circle"></i></a></div>
        </div>
    </div>
    <div class="swiper-container z-index-minus2 position-absolute top-0 one-third-screen" data-slider-options='{ "loop": true, "effect":"fade", "slidesPerView": "1", "allowTouchMove":true, "autoplay": { "delay": 5000, "disableOnInteraction": false }, "keyboard": { "enabled": true, "onlyInViewport": true }, "navigation": { "nextEl": ".swiper-button-next", "prevEl": ".swiper-button-prev" }, "pagination": { "el": ".swiper-pagination", "clickable": true } }'>
        <div class="swiper-wrapper">
            <!-- start slider item -->
            <div class="swiper-slide cover-background" style="background-image:url('{% static 'image2/digitalcarenetwork04.jpg' %}');"></div>
            <!-- end slider item -->
            <!-- start slider item -->
            <!-- <div class="swiper-slide cover-background" style="background-image:url('{% static 'image2/digitalcarenetwork19.jpg' %}');"></div> -->
            <!-- end slider item -->
            <!-- start slider item -->
            <div class="swiper-slide cover-background" style="background-image:url('{% static 'image2/digitalcarenetwork20.jpg' %}');"></div>
            <!-- end slider item -->
        </div>
        <!-- <div class="swiper-pagination"></div> -->
    </div>
</section>

<!-- end page title section -->
<!-- start section -->
<section class="wow animate__fadeIn last-paragraph-no-margin" style="margin-top:0rem;">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-12 col-lg-6 col-md-8 col-sm-9 text-center margin-70px-bottom md-margin-40px-bottom sm-margin-30px-bottom">
                <span class="alt-font text-deep-pink text-medium margin-5px-bottom d-block"> 디지털 환경에서의 사람들을 위한 연구소.</span>
                <h6 class="font-weight-400 text-extra-dark-gray alt-font mb-0">우리는 "디지털케어네트워크연구소" 입니다</h6>
            </div>
        </div>
        <div class="row margin-eight-bottom md-margin-30px-bottom">
            <div class="col-12 col-md-8 sm-margin-15px-bottom wow animate__fadeInLeft" data-wow-delay="0.2s">
                <img src="{% static 'image2/digitalcarenetwork06.jpg' %}" alt="" class="border-radius-6">
            </div>
            <div class="col-12 col-md-4 wow animate__fadeInRight" data-wow-delay="0.4s">
                <img src="{% static 'image2/about_Portrate.jpg' %}" alt="" class="border-radius-6 sm-w-100">
            </div>
        </div>
        <div class="row row-cols-1 row-cols-md-3 align-items-center">
            <div class="col sm-margin-15px-bottom">
                <span class="text-extra-large text-extra-dark-gray alt-font w-90 lg-w-95 md-w-100 d-block">디지털 환경 속에서 살아가는 사람들을<br>생각하고 돌보고자 하는 마음으로 다가가는<br>디지털케어네트워크 연구소</span>
            </div>
            <style>
              .text-extra-large {
    font-size: 15px;
    line-height: 24px;
    padding-left:2rem;
}
</style>
            <div class="col sm-margin-15px-bottom">
                <strong class="font-weight-600 text-extra-dark-gray margin-5px-bottom d-block alt-font">연구소 비전</strong>
                <p>디지털, 미디어, 기술에 대한 파르마콘적 사유를 통한 철학적 접근을 지향한다. 현대적, 서구적 기술과 비현대적 비서구적 사유에 대한 접점과 공명들을 심층적으로 탐색하면서, 한국 사회에 올바른 돌보기(Take-Care)와 다시 일으키기(Re-Start)작업을 추구한다.</p>
            </div>
            <div class="col">
                <strong class="font-weight-600 text-extra-dark-gray margin-5px-bottom d-block alt-font">임무</strong>
                <p>본 연구소의 추구상을 바탕으로, 오랫동안 우리의 삶에서 지배적이었던 디지털, 기술, 철학 담론과 비교되는 또 다른 사유의 다양함에 대하여 이야기 한다. 또한 이를 통한 새로운 시선, 사회 문화적 연대를 제안하며, 실천적 활동을 이행한다.</p>
            </div>
        </div>
    </div>
</section>
<!-- end section -->
<!-- start section -->
<section class="p-0  wow animate__fadeIn">
<!-- <section class="p-0 bg-light-gray wow animate__fadeIn"> -->
    <div class="container">
        <div class="row align-items-center">
            <div class="col-12 col-lg-5 order-1 order-lg-2 text-center text-lg-start offset-lg-1 md-padding-50px-all sm-padding-15px-lr">
                <i class="fas fa-quote-left text-deep-pink icon-medium margin-15px-bottom"></i>
                <h5 class="text-extra-dark-gray alt-font text-uppercase font-weight-700">이른바 4차 산업혁명의 시대에서<br>한국이 가진 고유한 기술의 사유와 실천들에 관한<br>현대적 의미는 무엇이 있을까?</h5>
                <p class="w-90 md-w-100">저희 디지털케어네트워크연구소에 오신 것을 환영합니다!<br>디지털케어네트워크연구소는 세계화된 단일 문화(Texhnological Monoculture)에 대한 실증적 분석과 이를 통한 기술적 사유와 체계의 다양성이라는 잠재성에 대하여 역설적으로 밝히고자 합니다.<br>현재 21세기 사회는 매일이 새롭게 글로벌, 미디어화되고 있다고 해도 과언이 아닙니다. 이제 현대사회는 디지털, 미디어와 함께 살아가고 있다고 말할 수 있죠. 이러한 시기에 디지털 미디어라는 스마트한 공간과 문화를 어떻게 생산하고 사유하는가는 매우 중요한 의제가 되었습니다. 저희 연구소는 이러한 디지털 환경을 "어떻게 잘 돌볼 것인가(Taking Care)"하는 철학적이며 인문학적인 핵심 아젠다를 던져보려고 합니다. 그리고 저희 연구소가 던지는 아젠다는 미디어 환경이 우리사회에 잘 자리하도록 일조할 수 있을 것입니다.</p>
                <img src="images/signature-dark.png" alt="" class="margin-15px-top">
                <span class="text-extra-dark-gray text-large d-block margin-30px-top alt-font font-weight-600">박성우</span>
                <span class="d-block">디지털케어네트워크 연구소장</span>
            </div>
            <div class="col-12 col-lg-6 order-2 order-lg-1 text-center align-self-end">
                <img src="{% static 'images/Seongu-Park.jpg' %}" alt="">
            </div>
        </div>
    </div>
</section><br><br><br>
<!-- end section -->
{% comment %}
<!-- start story section -->
<section class="wow animate__fadeIn">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-12 col-lg-5 col-md-6 text-center md-margin-30px-bottom wow animate__fadeInLeft">
                <img src="{% static 'images/Seongu-Park.jpg' %}" alt="" class="border-radius-6">
            </div>
            <div class="col-12 col-lg-7 col-md-6 text-center text-md-start padding-eight-lr lg-padding-six-lr md-padding-15px-lr wow animate__fadeInRight" data-wow-delay="0.2s">
                <span class="text-deep-pink alt-font margin-10px-bottom d-inline-block text-medium">연구소장 인사말</span>
                <h6 class="alt-font text-extra-dark-gray">우리의 접근 방식</h6>
                <p>디지털, 미디어, 기술에 대한 파르마콘적 사유를 통한 철학적 접근을 지향한다. 현대적, 서구적 기술과 비현대적 비서구적 사유에 대한 접점과 공명들을 심층적으로 탐색하면서, 한국 사회에 올바른 돌보기(Take-Care)와 다시 일으키기(Re-Start)작업을 추구한다.</p>
                <a href="services-simple.html" class="btn btn-dark-gray btn-small text-extra-small btn-rounded margin-5px-top"><i class="fas fa-play-circle icon-very-small margin-5px-right no-margin-left" aria-hidden="true"></i> Our Services</a>
            </div>
        </div>
        <div class="divider-full bg-extra-light-gray margin-seven-bottom margin-eight-top"></div>
    </div>
</section>
<!-- end story section -->
{% endcomment %}
<!-- start section -->
<!-- <section class="p-0 bg-light-gray wow animate__fadeIn">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-12 col-lg-5 order-1 order-lg-2 text-center text-lg-start offset-lg-1 md-padding-50px-all sm-padding-15px-lr">
                <i class="fas fa-quote-left text-deep-pink icon-medium margin-15px-bottom"></i>
                <h5 class="text-extra-dark-gray alt-font text-uppercase font-weight-700">Design is not just what it looks like and feels like. Design is how it works.</h5>
                <p class="w-90 md-w-100">Pofo philosophy that great design can only be delivered by people with a deep social and cultural understanding of the communities they designing. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever...</p>
                <img src="images/signature-dark.png" alt="" class="margin-15px-top">
                <span class="text-extra-dark-gray text-large d-block margin-30px-top alt-font font-weight-600">Colin Smith</span>
                <span class="d-block">From the chairman's desk</span>
            </div>
            <div class="col-12 col-lg-6 order-2 order-lg-1 text-center align-self-end">
                <img src="{% static 'images/Seongu-Park.jpg' %}" alt="">
            </div>
        </div>
    </div>
</section> -->
<!-- end section -->

<!-- start slider section  -->
<section id="clients" class="parallax wow animate__fadeIn" data-parallax-background-ratio="0.4" style="background-image:url('{% static 'image2/digitalcarenetwork06.jpg' %}');">
    <div class="opacity-medium bg-extra-dark-gray"></div>
    <div class="container">
        <div class="row">
            <div class="swiper-container white-move" data-slider-options='{ "slidesPerView": "1", "allowTouchMove":true,"paginationClickable": true, "autoplay": { "delay": 3000, "disableOnInteraction": true }, "navigation": { "nextEl": ".swiper-button-next", "prevEl": ".swiper-button-prev" }, "pagination": { "el": ".swiper-pagination", "clickable": true }, "breakpoints": { "1200": { "slidesPerView": 4 }, "992": { "slidesPerView": 3 }, "768": { "slidesPerView": 2 } }, "pagination": { "el": ".swiper-pagination" } }'>
                <!-- <div class="swiper-wrapper">
                    <div class="swiper-slide text-center"><a href="http://envato.com"><img src="{% static 'images/clients-logo1.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://woocommerce.com"><img src="{% static 'images/clients-logo2.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://wordpress.com"><img src="{% static 'images/clients-logo3.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://magento.com"><img src="{% static 'images/clients-logo4.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://envato.com"><img src="{% static 'images/clients-logo1.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://woocommerce.com"><img src="{% static 'images/clients-logo2.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://wordpress.com"><img src="{% static 'images/clients-logo3.png' %}" alt=""></a></div>
                    <div class="swiper-slide text-center"><a href="http://magento.com"><img src="{% static 'images/clients-logo4.png' %}" alt=""></a></div>
                </div> -->
                <!-- start swiper pagination -->
                <!-- <div class="swiper-pagination swiper-pagination-white"></div> -->
                <!-- end swiper pagination -->
            </div>
        </div>
    </div>
</section>
<!-- end slider section -->
<!-- start testimonial section -->
<section class="wow animate__fadeIn bg-light-gray testimonial-style3">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-12">
                <div class="row justify-content-center">
                    <div class="col-12 col-lg-4 col-md-6 col-sm-8 md-margin-two-bottom wow animate__fadeIn last-paragraph-no-margin testimonial-style3">
                        <div class="testimonial-content-box padding-twelve-all bg-white border-radius-6 box-shadow arrow-bottom lg-padding-nine-all md-padding-eight-all">
                            I wanted to hire the best and after looking at several other companies, I knew Jacob was the perfect guy for the job. He is a true professional.
                        </div>
                        <!-- start testimonials item -->
                        <div class="testimonial-box padding-25px-all sm-padding-20px-all">
                            <div class="image-box w-20"><img src="https://via.placeholder.com/149x149" class="rounded-circle" alt=""></div>
                            <div class="name-box padding-20px-left">
                                <div class="alt-font font-weight-600 text-small text-uppercase text-extra-dark-gray">Shoko Mugikura</div>
                                <p class="text-extra-small text-uppercase text-medium-gray">Graphic Designer</p>
                            </div>
                        </div>
                    </div>
                    <!-- end testimonials item -->
                    <!-- start testimonials item -->
                    <div class="col-12 col-lg-4 col-md-6 col-sm-8 md-margin-two-bottom wow animate__fadeIn last-paragraph-no-margin testimonial-style3" data-wow-delay="0.2s">
                        <div class="testimonial-content-box padding-twelve-all bg-white border-radius-6 box-shadow arrow-bottom lg-padding-nine-all md-padding-eight-all">
                            This is an excellent company! I personally enjoyed the energy and the professional support the whole team gave to us into creating website.
                        </div>
                        <div class="testimonial-box padding-25px-all sm-padding-20px-all">
                            <div class="image-box w-20"><img src="https://via.placeholder.com/149x149" class="rounded-circle" alt=""></div>
                            <div class="name-box padding-20px-left">
                                <div class="alt-font font-weight-600 text-small text-uppercase text-extra-dark-gray">Alexander Harvard</div>
                                <p class="text-extra-small text-uppercase text-medium-gray">Creative Director</p>
                            </div>
                        </div>
                    </div>
                    <!-- end testimonials item -->
                    <!-- start testimonials item -->
                    <div class="col-12 col-lg-4 col-md-6 col-sm-8 wow animate__fadeIn last-paragraph-no-margin testimonial-style3" data-wow-delay="0.4s">
                        <div class="testimonial-content-box padding-twelve-all bg-white border-radius-6 box-shadow arrow-bottom lg-padding-nine-all md-padding-eight-all">
                            Their team are easy to work with and helped me make amazing websites in a short amount of time. Thanks again guys for all your hard work.
                        </div>
                        <div class="testimonial-box padding-25px-all sm-padding-20px-all">
                            <div class="image-box w-20"><img src="https://via.placeholder.com/149x149" class="rounded-circle" alt=""></div>
                            <div class="name-box padding-20px-left">
                                <div class="alt-font font-weight-600 text-small text-uppercase text-extra-dark-gray">Herman Miller</div>
                                <p class="text-extra-small text-uppercase text-medium-gray">Co Founder / CEO</p>
                            </div>
                        </div>
                    </div>
                    <!-- end testimonials item -->
                </div>
            </div>
        </div>
    </div>
</section>
<!-- end testimonial section -->
<!-- start team section -->
<section class="wow animate__fadeIn">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-12 col-xl-7 col-lg-8 col-md-10 margin-eight-bottom md-margin-40px-bottom sm-margin-30px-bottom text-center">
                <div class="alt-font text-medium-gray margin-5px-bottom text-uppercase text-small">건강한 디지털 세상을 이끌어가기 위해 활동하는 사람들</div>
                <h5 class="alt-font text-extra-dark-gray font-weight-600 mb-0">소속 연구원</h5>
            </div>
        </div>
        <div class="row row-cols-1 row-cols-lg-4 row-cols-sm-2 justify-content-center">
            <!-- start team item -->
            <div class="col team-block text-start team-style-1 md-margin-seven-bottom sm-margin-30px-bottom wow animate__fadeInRight">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="https://via.placeholder.com/700x892" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">우송대학교 글로벌미디어영상학과 학과장<br>(Department of Media communication and Arts, Woosong University)<br>방송문화연구전공(Media Cultural Studies)</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="http://www.facebook.com" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                                <a href="mailto:licjpsw@gmail.com" target="_blank" class="text-white-2"><i class="fas fa-envelope"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">박성우 / Park Sungwoo</div>
                            <div class="text-extra-small text-uppercase text-medium-gray">연구소장</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->
            <!-- start team item -->
            <div  class="col team-block text-start team-style-1  wow animate__fadeInRight" data-wow-delay="0.2s">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="{% static 'images2/profile-jason.jpg' %}" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">연세대학교 커뮤니케이션대학원 미디어문화연구전공<br>(M.A. of Media Cultural Studies, Yonsei University Graduate School of Communication Arts)<br>관심분야: 학력차별, 공간과 미디어</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="https://www.facebook.com/sunghyunbook/" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.twitter.com" target="_blank" class="text-white-2"><i class="fab fa-twitter"></i></a>
                                <a href="mailto:parksunghyunw@yonsei.ac.kr" target="_blank" class="text-white-2"><i class="fas fa-envelope"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">박성현 / Park Sunghyun</div>
                            <div class="text-extra-small text-uppercase text-medium-gray">연구원</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->
            <!-- start team item -->
            <div class="col team-block text-start team-style-1 wow animate__fadeInRight" data-wow-delay="0.4s">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="https://via.placeholder.com/700x892" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">Lorem Ipsum is simply dummy text of the printing and typesetting industry dummy text.</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="http://www.facebook.com" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.twitter.com" target="_blank" class="text-white-2"><i class="fab fa-twitter"></i></a>
                                <a href="http://www.plus.google.com" target="_blank" class="text-white-2"><i class="fab fa-google-plus-g"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">스톰 / Schutte Storm </div>
                            <div class="text-extra-small text-uppercase text-medium-gray">연구원</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->
            <!-- start team item -->
            <div class="col team-block text-start team-style-1 wow animate__fadeInRight" data-wow-delay="0.4s">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="https://via.placeholder.com/700x892" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">Lorem Ipsum is simply dummy text of the printing and typesetting industry dummy text.</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="http://www.facebook.com" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.twitter.com" target="_blank" class="text-white-2"><i class="fab fa-twitter"></i></a>
                                <a href="http://www.plus.google.com" target="_blank" class="text-white-2"><i class="fab fa-google-plus-g"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">노현진</div>
                            <div class="text-extra-small text-uppercase text-medium-gray">연구원</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->


        </div>
    </div>
</section>
<!-- end team section -->
<!-- start team section -->
<section style="margin-top:-10rem;" class="wow animate__fadeIn">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-12 col-xl-7 col-lg-8 col-md-10 margin-eight-bottom md-margin-40px-bottom sm-margin-30px-bottom text-center">
                <h5 class="alt-font text-extra-dark-gray font-weight-600 mb-0">연구 위원</h5>
            </div>
        </div>
        <div class="row row-cols-1 row-cols-lg-4 row-cols-sm-2 justify-content-center">
            <!-- start team item -->
            <div class="col team-block text-start team-style-1 md-margin-seven-bottom sm-margin-30px-bottom wow animate__fadeInRight">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="https://via.placeholder.com/700x892" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">Lorem Ipsum is simply dummy text of the printing and typesetting industry dummy text.</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="http://www.facebook.com" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.twitter.com" target="_blank" class="text-white-2"><i class="fab fa-twitter"></i></a>
                                <a href="http://www.plus.google.com" target="_blank" class="text-white-2"><i class="fab fa-google-plus-g"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">조형준 / Cho Hyeongjun</div>
                            <div class="text-extra-small text-uppercase text-medium-gray">새물결출판사 주간</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->
            <!-- start team item -->
            <div class="col team-block text-start team-style-1 md-margin-seven-bottom sm-margin-30px-bottom wow animate__fadeInRight" data-wow-delay="0.2s">
                <figure>
                    <div class="team-image sm-w-100">
                        <img src="https://via.placeholder.com/700x892" alt="">
                        <div class="overlay-content text-center d-flex align-items-end justify-content-center">
                            <div class="icon-social-small padding-twelve-all">
                                <span class="text-white-2 text-small d-inline-block m-0">Lorem Ipsum is simply dummy text of the printing and typesetting industry dummy text.</span>
                                <div class="separator-line-horrizontal-full bg-deep-pink margin-eleven-tb"></div>
                                <a href="http://www.facebook.com" target="_blank" class="text-white-2"><i class="fab fa-facebook-f"></i></a>
                                <a href="http://www.twitter.com" target="_blank" class="text-white-2"><i class="fab fa-twitter"></i></a>
                                <a href="http://www.plus.google.com" target="_blank" class="text-white-2"><i class="fab fa-google-plus-g"></i></a>
                                <a href="http://www.instagram.com" target="_blank" class="text-white-2"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>
                        <div class="team-overlay bg-extra-dark-gray opacity8"></div>
                    </div>
                    <figcaption>
                        <div class="team-member-position margin-20px-top text-center">
                            <div class="text-small font-weight-500 text-extra-dark-gray text-uppercase">Yuk Hui / 허욱</div>
                            <div class="text-extra-small text-uppercase text-medium-gray">철학자, 홍콩</div>
                        </div>
                    </figcaption>
                </figure>
            </div>
            <!-- end team item -->
        </div>
    </div>
</section>
<!-- end team section -->


{% endblock %}
