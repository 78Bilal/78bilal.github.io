<!DOCTYPE html>
    <html lang="tr">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!--=============== FAVICON ===============-->
        <link rel="shortcut icon" href="assets/img/favicon.png" type="image/x-icon">
        
        <!--=============== REMIX ICONS ===============-->
        <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css"rel="stylesheet"/>

        <!--=============== CSS ===============-->
        <link rel="stylesheet" href="assets/css/styles.css">

        <title>Mini portfolio website - MBK Technology</title>
    </head>
    <body>
        <!--=============== HEADER PROFILE ===============-->
        <header class="profile container">
            <!-- Theme button -->
            <i class="ri-moon-line change-theme" id="theme-button"></i>


            <div class="profile__container grid">
                <div class="profile__data">
                    <div class="profile__border">
                        <div class="profile__perfil">
                            <img src="assets/img/perfil.png" alt="">
                        </div>
                    </div>

                    <h2 class="profile__name">Muhammed Bilal KÜÇÜKKARA</h2>
                    <h3 class="profile__profession">Web developer</h3>

                    <ul class="profile__social">
                        <a href="https://www.instagram.com/bilal78k" target="_blank" class="profile__social-link">
                            <i class="ri-instagram-line"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/muhammed-bilal-küçükkara-b2bab8309" target="_blank" class="profile__social-link">
                            <i class="ri-linkedin-box-line"></i>
                        </a>
                        <a href="https://github.com/78Bilal" target="_blank" class="profile__social-link">
                            <i class="ri-github-line"></i>
                        </a>
                    </ul>
                </div>

                <div class="profile__info grid">
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">3</h3>
                        <p class="profile__info-description">Yıl iş <br> Deneyimi</p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">+78</h3>
                        <p class="profile__info-description">Tamamlanan <br> Proje</p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">60</h3>
                        <p class="profile__info-description">Memnun <br> Müşteri</p>
                    </div>
                </div>

                <div class="profile__buttons">
                    <a download="" href="assets/pdf/Bilal-Cv.pdf" class="button">CV İndir<i class="ri-download-line"></i>
                    </a>

                    <div class="profile__buttons-small">
                        <a href="https://api.whatsapp.com/send?phone=905516438419&text=Hello, more information!" target="_blank" class="button button__small button__gray">
                            <i class="ri-whatsapp-line"></i>
                        </a>
                        <a href="https://m.me/mbktechnology" target="_blank" class="button button__small button__gray">
                            <i class="ri-messenger-line"></i>
                        </a>
                    </div>
                </div>
            </div>
        </header>

        <!--=============== MAIN ===============-->
        <main class="main">
            <section class="filters container">
                <!--=============== FILTERS TABS ===============-->
                <ul class="filters__content">
                    <button class="filters__button filter-tab-active" data-target="#projects">
                        Projeler
                    </button>
                    <button class="filters__button" data-target="#skills">
                        Yetenekler
                    </button>
                </ul>
                <div class="filters__sections">
                    <!--=============== PROJECTS ===============-->
                    <div class="projects__content grid filters__active" data-content id="projects">
                        <article class="projects__card">
                            <img src="assets/img/project1.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Web</span>
                                    <h3 class="projects__title">Blog Sitesi</h3>
                                    <a href="https://bilaltech.my.canva.site/" target="_blank" class="projects__button button button__small"><i class="ri-link"></i></a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project2.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Web</span>
                                    <h3 class="projects__title">Portfolyo Sitesi</h3>
                                    <a href="https://bilal78.bio.link" target="_blank" class="projects__button button button__small"><i class="ri-link"></i></a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project3.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Arduino</span>
                                    <h3 class="projects__title">Deprem Alarmı Sensörü
                                    </h3>
                                    <a href="https://github.com/78Bilal/deprem_alarmi_projesi" target="_blank" class="projects__button button button__small"><i class="ri-link"></i></a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project4.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">C#</span>
                                    <h3 class="projects__title">Otobüs Bilet Satış
                                    </h3>
                                    <a href="https://github.com/78Bilal/Otobus_Bilet_Satis_Programi/" target="_blank" class="projects__button button button__small"><i class="ri-link"></i></a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project5.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Tasarım</span>
                                    <h3 class="projects__title">Karabük Tanıtım Dergisi
                                    </h3>
                                    <a href="https://online.fliphtml5.com/coagx/tlmg/" target="_blank" class="projects__button button button__small"><i class="ri-link"></i></a>
                                </div>
                            </div>
                        </article>
                    </div>

                    <!--=============== SKILLS ===============-->
                    <div class="skills__content grid " data-content id="skills">
                        <div class="skills__area">
                            <h3 class="skills__title">
                                Frontend Geliştirici
                            </h3>

                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">HTML</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">CSS</h3>
                                            <span class="skills__level">Advanced</span>
                                        </div>
                                    </div>

                                    
                                </div>

                                <div class="skills__group">
                                    
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">javaScript</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Git</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="skills__area">
                            <h3 class="skills__title">
                                Backend Geliştirici
                            </h3>

                            <div class="skills__box">
                                <div class="skills__group">

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">MySQL</h3>
                                            <span class="skills__level">Advanced</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Firebase</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>

                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Python</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>


                                </div>
                            </div>
                        </div>
                    </div>


                </div>
            </section>
        </main>

        <!--=============== FOOTER ===============-->
        <footer class="footer container">
            <span class="footer__copy">
                &#169; MBK Technology. All rigths reserved

            </span>
        </footer>

        <!--=============== SCROLLREVEAL ===============-->
        <script src="assets/js/scrollreveal.min.js"></script>

        <!--=============== MAIN JS ===============-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
