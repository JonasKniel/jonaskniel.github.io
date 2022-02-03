<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">

        <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900" rel="stylesheet">

        <link rel="stylesheet" href="css/style.css">
        <link rel="shortcut icon" type="image/png" href="img/Asset 1@2x.png">
        
        <title>Portfolio of Jonas Kniel | UX Product Manager at Shape Republic</title>

        <script>
            function uncheck()
            {
            document.getElementById('navi-toggle').checked=false;
            }
        </script>
    </head>

    <body>
        <div class="navigation">
            <input type="checkbox" class="navigation__checkbox" id="navi-toggle">

            <label for="navi-toggle" class="navigation__button">
                <span class="navigation__icon">&nbsp;</span>
            </label>

            <div class="navigation__background">&nbsp;</div>

            <nav class="navigation__nav">
                <ul class="navigation__list">
                    <li class="navigation__item"><a href="#about-me" class="navigation__link smoothScroll" onclick="uncheck()"><span>01</span>About Me</a></li>
                    <li class="navigation__item"><a href="#in-the-news" class="navigation__link smoothScroll" onclick="uncheck()"><span>02</span>In the News</a></li>
                    <li class="navigation__item"><a href="#case-studies" class="navigation__link smoothScroll" onclick="uncheck()"><span>03</span>Case Studies</a></li>
                    <li class="navigation__item"><a href="#connect" class="navigation__link smoothScroll" onclick="uncheck()"><span>04</span>Connect</a></li>
                    <li class="navigation__item"><a href="https://jonaskniel.wordpress.com/" target="_blank" class="navigation__link smoothScroll" onclick="uncheck()"><span>05</span>My Blog</a></li>
                </ul>
            </nav>
        </div>

        <header class="header">
            <div class="header__logo-box">
                <img src="img/logo-white-2x.png" alt="Logo" class="header__logo">
            </div>

            <div class="header__text-box">
                <h1 class="heading-primary">
                    <span class="heading-primary--main">User Centred working</span>
                    <span class="heading-primary--sub">My mission is to drive conversions while delighting users</span>
                </h1>
            </div>
        </header>

        <main>
            <section class="section-about">
                <div class="u-center-text u-margin-bottom-big">
                    <h2 class="heading-secondary" id="about-me">
                        Hi I'm Jonas 👋🏻
                    </h2>
                </div>

                <div class="row">
                    <div class="col-1-of-2">
                        <h3 class="heading-tertiary u-margin-bottom-small">About me</h3>
                        <p class="paragraph">
                            Mechanical engineer turned product enthusiast with a master focussing on management in tech and design. Since graduating with distinction in 2019 I have been working as a user researcher and product manager. Right now, at Shape Republic I help build an e-commerce experience which has been awarded the Shop Usability award 2020 and featured on Shopify.
                        </p>

                        <h3 class="heading-tertiary u-margin-bottom-small">My values</h3>
                        <p class="paragraph">
                            1. When exploring a new feature/concept trust the <a href="https://softskillsfordesigners.com/wp-content/uploads/2016/07/Screen-Shot-2016-06-28-at-5.48.19-PM-2-1024x444.png" class="btn-text" target="_blank">process</a> and that it will take you through the uncertainty into a productive space.<br>
                            2. Work towards <a href="https://jonaskniel.wordpress.com/2019/03/05/how-to-lead-for-creative-resonance/" target="_blank" class="btn-text">creative resonance</a> because what you can achieve by collaborating will always be more valuable than what you can acheive by yourself<br>
                            3. It is better to <a href="https://www.pacific-research.com/wp-content/uploads/2020/09/Iterative-product-development-process.png" class="btn-text" target="_blank">ship earlier & make one more iteration</a> based on user feedback than to perfect in your isolated chamber.<br>
                        </p>
                    </div>
                    <div class="col-1-of-2">
                        <div class="intro">
                            <div class="intro__picture">
                                <img src="img/profile_pic_small.jpg" alt="Jonas Kniel Profile Pic" class="intro__pic">
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section class="section-features">
                <div class="u-center-text u-margin-bottom-big">
                    <h2 class="heading-secondary heading-secondary__white" id="in-the-news">
                        In the News
                    </h2>
                    <h3 class="heading-tertiary heading-tertiary__white ">A selection from blogs and websites featuring my work.</h3>
                </div>

                <div class="row">

                    <div class="col-1-of-3">
                        <div class="feature-box">
                            <a href="https://www.shopify.de/beispiele?category=food-and-drink-templates#ExampleTabWrapper" class="feature-box__link">
                                <img class="feature-box__image" src="img/shopify-logo-white.png">
                                <div class="feature-box__text-container">
                                    <div class="feature-box__heading u-margin-bottom-small">
                                        <h3 class="heading-tertiary">Shopify</h3>
                                        <span>04.2021</span>
                                    </div>
                                    <p class="feature-box__text">
                                        Shape Republic is featured on Shopify as a inspiration source for new customers of what can be built with the Plattform.
                                    </p>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="col-1-of-3">
                        <div class="feature-box">
                            <a href="https://uxme.io/interviews/jonas-kniel-von-shape-republic-im-interview-gewinner-beim-shop-usability-award-2020" class="feature-box__link">
                                <img class="feature-box__image" src="img/uxme-community.png">
                                <div class="feature-box__text-container">
                                    <div class="feature-box__heading u-margin-bottom-small">
                                        <h3 class="heading-tertiary">UXME</h3>
                                        <span>01.2021</span>
                                    </div>
                                    <p class="feature-box__text">
                                        Interview with the Design Community UxMe on the Design success of Shape Republic (Text in German)
                                    </p>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="col-1-of-3">
                        <div class="feature-box">
                            <a href="https://uxme.io/shops/https-www-shape-republic-com/submissions/1163" class="feature-box__link">
                                <img class="feature-box__image" src="img/Winner-pic.png">
                                <div class="feature-box__text-container">
                                    <div class="feature-box__heading u-margin-bottom-small">
                                        <h3 class="heading-tertiary">Shop Usability Award</h3>
                                        <span>09.2020</span>
                                    </div>
                                    <p class="feature-box__text">
                                    Shape Republic is awarded the German Shop Usability Award 2020 in the Category of Food and Drinks.
                                    </p>
                                </div>
                            </a>    
                        </div>
                    </div>
                </div>
            </section>

            <section class="section-tours">
                <div class="u-center-text u-margin-bottom-big">
                    <h2 class="heading-secondary" id="case-studies">
                        Case Studies
                    </h2>

                    <h3 class="heading-tertiary">Discover my collection of past work and design challenges.</h3>
                    
                </div>

                <div class="row">
                    <div class="col-1-of-3">
                       <div class="card">
                           <div class="card__side card__side--front">
                                <div class="card__picture card__picture--1">
                                    &nbsp;
                                </div>
                                <h4 class="card__heading">
                                    <span class="card__heading-span card__heading-span--1">Improving a Referral Program</span>
                                </h4>
                                <div class="card__details">
                                    <ul>
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-briefcase"></use>
                                                </svg>Company:</div>
                                                <div class="detail__value">Coya (Insurance)</div>
                                            </div>
                                        </li>
                
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-clock"></use>
                                                </svg>Timeframe:</div>
                                                <div class="detail__value">8 Weeks</div>
                                            </div>
                                        </li>

                                        <li><div class="tag__group"><div class="tag__1">Strategy</div><div class="tag__2">UX-Research</div><div class="tag__3">UX-Design</div></div></li>

                                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque perferendis quidem dolorem. Quasi voluptatum.</li>
                                    </ul>
                                </div>
                           </div>
                           <div class="card__side card__side--back card__side--back-1">
                                <div class="card__cta">
                                    <a href="https://spectrum-othnielia-4f8.notion.site/Improving-Coya-s-Referral-Program-df3660b8fea24ce2b41d95f1eebc59f3" target="_blank" class="btn btn--white">To the Case Study</a>
                                </div>
                            </div>
                       </div>
                    </div>


                    <div class="col-1-of-3">
                        <div class="card">
                            <div class="card__side card__side--front">
                                <div class="card__picture card__picture--2">
                                    &nbsp;
                                </div>
                                <h4 class="card__heading">
                                    <span class="card__heading-span card__heading-span--2">Redesigning a Trial offering</span>
                                </h4>
                                <div class="card__details">
                                    <ul>
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-briefcase"></use>
                                                </svg>Company:</div>
                                                <div class="detail__value">Coya (Insurance)</div>
                                            </div>
                                        </li>
                
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-clock"></use>
                                                </svg>Timeframe:</div>
                                                <div class="detail__value">6 Weeks</div>
                                            </div>
                                        </li>

                                        <li><div class="tag__group"><div class="tag__1">UX-Research</div><div class="tag__2">Facilitation</div><div class="tag__3">Strategy</div></div></li>

                                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque perferendis quidem dolorem. Quasi voluptatum.</li>
                                    </ul>
                                </div>

                            </div>
                            <div class="card__side card__side--back card__side--back-2">
                                <div class="card__cta">
                                    <a href="https://spectrum-othnielia-4f8.notion.site/Redesigning-Coya-s-Free-Trial-Offering-7a0887ec3e064412ba4659795e6322d7" target="_blank" class="btn btn--white">To the Case Study</a>
                                </div>
                            </div>
                        </div>
                    </div>


                    <div class="col-1-of-3">
                        <div class="card">
                            <div class="card__side card__side--front">
                                <div class="card__picture card__picture--3">
                                    &nbsp;
                                </div>
                                <h4 class="card__heading">
                                    <span class="card__heading-span card__heading-span--3">Making Easyjet Futureproof</span>
                                </h4>
                                <div class="card__details">
                                    <ul>
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-briefcase"></use>
                                                </svg>Company:</div>
                                                <div class="detail__value">Easyjet (Case Study)</div>
                                            </div>
                                        </li>
                
                                        <li>
                                            <div class="detail">
                                                <div class="detail__description"><svg class="icon">
                                                    <use xlink:href="img/sprite.svg#icon-clock"></use>
                                                </svg>Timeframe:</div>
                                                <div class="detail__value">7 Days</div>
                                            </div>
                                        </li>

                                        <li><div class="tag__group"><div class="tag__1">Strategy</div><div class="tag__2">UX-Research</div><div class="tag__3">UX-Design</div></div></li>

                                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque perferendis quidem dolorem. Quasi voluptatum.</li>
                                    </ul>
                                </div>

                            </div>
                            <div class="card__side card__side--back card__side--back-3">
                                <div class="card__cta">
                                    <a href="https://spectrum-othnielia-4f8.notion.site/Personal-Design-Challenge-Making-Easyjet-s-Android-App-Futureproof-a593811c82a043a09b0596b2befdabb8" target="_blank" class="btn btn--white">To the Case Study</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section class="section-contact">
                <div class="row">
                    <div class="contact">
                        <div class="contact__wrapper">
                            <div class="u-center-text u-margin-bottom-medium">
                                <h2 class="heading-secondary" id="connect">
                                    Let's connect
                                </h2>
                                <h3 class="heading-tertiary"><div class="section-headline-subtext">Reach out to chat about the latest trends in the UX world or grab a bowl of ramen somewhere in Berlin.</div></h3>
                            </div>
                        </div>

                        <div class="contact__options">
                            <div class="contact__options-group">
                                <div class="contact__email">
                                    <svg class="icon__bigger">
                                        <use xlink:href="img/sprite.svg#icon-envelope"></use>
                                    </svg>
                                    <a href="mailto: jonas@kniel.org" class="contact__detail">jonas@kniel.org</a>
                                </div>
                            </div>
                            <div class="contact__options-group">
                                <div class="contact__phone">
                                    <svg class="icon__bigger">
                                        <use xlink:href="img/sprite.svg#icon-phone"></use>
                                    </svg>
                                    <a href="tel: +4915251305339" class="contact__detail">+49 1525 1305339</a>
                                </div>
                            </div>

                            <div class="contact__options-group">
                                <div class="contact__location">
                                    <svg class="icon__bigger">
                                        <use xlink:href="img/sprite.svg#icon-map-pin"></use>
                                    </svg>
                                    <a href="#" class="contact__detail">10997, Berlin</a>
                                </div>
                            </div>

                            <div class="contact__options-group">
                                <div class="contact__linkedin">
                                    <svg class="icon__bigger">
                                        <use xlink:href="img/sprite.svg#icon-linkedin"></use>
                                    </svg>
                                    <a href="https://www.linkedin.com/in/jonas-kniel/" target="_blank" class="contact__detail">Jonas Kniel</a>
                                </div>
                            </div>
                            <div class="contact__options-group">
                                <div class="contact__divider"></div>
                            </div>

                            <div class="contact__options-group">
                                <div class="contact__resume">
                                    <svg class="icon__bigger">
                                        <use xlink:href="img/sprite.svg#icon-paperclip"></use>
                                    </svg>
                                    <a href="#" class="contact__detail">Resume</a>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer class="footer">
            <div class="footer__logo-box">

                <picture class="footer__logo">
                    <img src="img/logo-white-2x.png" alt="Logo" class="header__logo">
                </picture>

                
            </div>
            <div class="row">
                <div class="col-1-of-2">
                    <div class="footer__navigation">
                        <ul class="footer__list">
                            <li class="footer__item"><a href="#about-me" class="btn-text__light smoothScroll">About Me</a></li>
                            <li class="footer__item"><a href="#in-the-news" class="btn-text__light smoothScroll">In the News</a></li>
                            <li class="footer__item"><a href="#case-studies" class="btn-text__light smoothScroll">Case Studies</a></li>
                            <li class="footer__item"><a href="#connect" class="btn-text__light smoothScroll">Connect</a></li>
                            <li class="footer__item"><a href="https://jonaskniel.wordpress.com/" target="_blank" class="btn-text__light smoothScroll">My Blog</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-1-of-2">
                    <p class="footer__copyright">
                        Built by <a href="https://www.youtube.com/watch?v=bSfpSOBD30U" class="btn-text__light">Me Myself And I</a>. With love from Berlin.
                    </p>
                </div>
            </div>
        </footer>

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
        <script>
        $(document).ready(function(){
          // Add smooth scrolling to all links
          $("a").on('click', function(event) {
        
            // Make sure this.hash has a value before overriding default behavior
            if (this.hash !== "") {
              // Prevent default anchor click behavior
              event.preventDefault();
        
              // Store hash
              var hash = this.hash;
        
              // Using jQuery's animate() method to add smooth page scroll
              // The optional number (800) specifies the number of milliseconds it takes to scroll to the specified area
              $('html, body').animate({
                scrollTop: $(hash).offset().top
              }, 800, function(){
        
                // Add hash (#) to URL when done scrolling (default click behavior)
                window.location.hash = hash;
              });
            } // End if
          });
        });
        </script>
    </body>
</html>
