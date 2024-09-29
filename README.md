# swecker325.github.io
Week Two Final Project - 1:1 Treact Website


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="finalstyle.css">
    <script src="index.js"></script>
    <script
    src="https://kit.fontawesome.com/690b14d31b.js"
    crossorigin="anonymous"
  ></script>
    <title>Final Project2</title>
</head>
<main>
<body>
<div id="root">
                   <div class="row">

                       <nav class="nav_one">
                           <div class="nav__container">
                               <div class="logo">

                                   <img src="./assets/FinalLogo.svg" class="logo" alt=""><h3 class="treact__size">Treact</h3>
                                </div>
                          
                            
                            <div class="nav__container--two">
                                <ul class="nav__link--list">
                                    <li>
                                        
                                        <a href="#about" class="
                                        nav__link--anchor 
                                        link__hover-effect 
                                        link__hover-effect--black">
                                        About</a>
                                    </li>
                                    <li>
                                        
                                        <a href="#blog" class="
                                        nav__link--anchor 
                                        link__hover-effect 
                                        link__hover-effect--black">
                                        Blog</a> 
                                    </li>
                                    <li>
                                        
                                        <a href="#pricing" class="
                                        nav__link--anchor 
                                        link__hover-effect 
                                        link__hover-effect--black">
                                        Pricing</a>
                                    </li>
                                    <li>
                                        
                                        <a href="#contact" class="
                                        nav__link--anchor 
                                        link__hover-effect 
                                        link__hover-effect--black">
                                        Contact Us</a>
                                    </li>
                                    <li>
                                        
                                        <a href="#pricing" class="
                                        nav__link--anchor
                                        link__hover-effect 
                                        link__hover-effect--black">
                                        Login</a>
                                    </li>
                                    <li>
    
                                        <a href="#pricing" class="
                                        nav__link--anchor 
                                        nav__link--anchor-primary">
                                        Sign Up </a>
                                    </li>
                                </ul>
</div>


<button class="btn__menu" onclick="openMenu()">
    <i class="fa-solid fa-bars"></i>
</button>


<div class="menu__backdrop">
    <button class="btn__menu btn__menu--close" onclick="closeMenu()">
        <i class="fas fa-times"></i>
    </button>
    <ul class="menu__links">
        <li class="menu__list">
            <a href="#" class="menu__link" onclick="closeMenu()">About</a>
        </li>
        <li class="menu__list">
            <a href="#" class="menu__link" onclick="closeMenu()">Blog</a>
        </li>
        <li class="menu__list">
            <a href="#" class="menu__link" onclick="closeMenu()">Pricing</a>
        </li>
        <li class="menu__list">
            <a href="#" class="menu__link" onclick="closeMenu()">Contact Us</a>
        </li>
        <li class="menu__list">
            <a href="#" class="menu__link" onclick="closeMenu()">Login</a>
        </li>
        <li class="menu__list">
            <a href="#" class="menu__link sign__up--menu" onclick="closeMenu()">Sign Up</a>
        </li>
    </ul>     
</div> 
                           </div>
                           

</nav>     

</header>
<div>
    <div class="row">
        <div class="home__description">

            <div class="about-company__info--container">
                <img class="treact__picture" src="./assets/design-illustration-2.6da6a00b20c07c4a9b65d1870679e1b8.svg" alt="">
                <div class="info__intro">
                    <h1 class="header__one">Beautiful React Templates <span class="text--purple">for you </span></h1>
                    <p class="info__intro--para">Our templates are easy to setup, understand and customize. Fully modular components with a variety of pages and components.</p>
                    <div class="email__box">
                        <div class="get__started__button">
                        <input type="email" class="email__box--primary" placeholder="Your E-mail Address" fdprocessedid="kd0g3p"> 

                            <button class="start__button"> Get Started</button>
                        </div>
                    </div>
                    <div class="customers__wrapper">
                        <p class="trusted">
                            OUR TRUSTED CUSTOMERS
                        </p>
                        <div class="customer__logo__container">
                            
                            <img class="customer__logo" src="./assets/customers-logo-strip.680ac7c2e8ae28161d2c.png" alt="">
                        </div>
                    </div>
                        
                </div>
            </div>
        </div>
    </div>
    </section>
   
    <section>
    <div class="row">
        <div class="threecollumn__container">
            <div class="threecollumn__row">
                <h5 class="header__two"><span class="text--purple"> FEATURES</span></h5>
                <h1 class="section__title">We have Amazing <span class="text--purple">Service</span></h2>
                <p class="subheader">
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui minima reiciendis nam quod id sapiente lorem lorem lorel lorl diden </p>
                    <div class="highlight__wrapper">
                        
                        <div class="highlight__container__each">
                            
                            <div class="highlight">
                                <div class="highlight__img">
                                    <i class="fa-solid fa-shield-halved"></i>
                                </div>
                                <div class="text__container">
                                    
                                    <h3 class="highlight__subtitle">
                                        Secure
                                    </h3>
                                    <p class="highlight__para">
                                        We strickly only deal with vendors that provide top notch security.
                                    </p>    
                                </div>
                            </div>
                        </div>
                        
                        <div class="highlight__container__each">
                            
                            <div class="highlight">
                                <div class="highlight__img">
                                    <i class="fa-brands fa-intercom"></i>
                                </div>
                                <div class="text__container">
                                    
                                    <h3 class="highlight__subtitle">
                                        24/7 Support
                                    </h3>
                                    <p class="highlight__para">
                                        We strickly only deal with vendors that provide top notch security.
                                    </p>    
                                </div>
                            </div>
                        </div>
                        
                        
                            <div class="highlight__container__each">
                                
                                <div class="highlight">
                                    <div class="highlight__img">
                                        <i class="fa-solid fa-shield-halved"></i>
                                    </div>
                                    <div class="text__container">
                                        
                                        <h3 class="highlight__subtitle">
                                            Customizable
                                        </h3>
                                        <p class="highlight__para">
                                            We strickly only deal with vendors that provide top notch security.
                                        </p>    
                                    </div>
                                </div>
                            </div>
                            
                            
                            <div class="highlight__container__each">
                                
                                <div class="highlight">
                                    <div class="highlight__img">
                                        <i class="fa-solid fa-up-right-and-down-left-from-center"></i>
                                    </div>
                                    <div class="text__container">
                                        
                                        <h3 class="highlight__subtitle">
                                            Reliable
                                        </h3>
                                        <p class="highlight__para">
                                            We strickly only deal with vendors that provide top notch security.
                                        </p>    
                                    </div>
                                </div>
                            </div>
                            
                            
                            <div class="highlight__container__each">
                                
                                <div class="highlight">
                                <div class="highlight__img">
                                    <i class="fa-solid fa-bolt-lightning"></i>
                                </div>
                                <div class="text__container">
                                    
                                    <h3 class="highlight__subtitle">
                                        Fast
                                    </h3>
                                    <p class="highlight__para">
                                        We strickly only deal with vendors that provide top notch security.
                                    </p>    
                                </div>
                            </div>
                        </div>
                        
                        <div class="highlight__container__each">
                            
                            <div class="highlight">
                                <div class="highlight__img">
                                    <i class="fa-regular fa-handshake"></i>
                                </div>
                                <div class="text__container">
                                    
                                    <h3 class="highlight__subtitle">
                                        Easy
                                    </h3>
                                    <p class="highlight__para">
                                        We strickly only deal with vendors that provide top notch security.
                                    </p>    
                                </div>
                            </div>
                        </div>
                        
                    </div>
                </div>
            </div>
        </div>
            </section>
            
            
            <section>
                <div class="row">
                    <div class="section__two__container">
                        <div class="column__wrapper">

                            <div class="section__two">
                                <h5 class="title__two"> <span class="text--purple">
                                    QUALITY WORK
                                </span>
                            </h5>
                            <h2 class="subheader__two">Desgined & Developed by
                                <span class="text--purple"> Professionals</h2></span>
                                <p class="subheader__para">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Harum voluptatibus provident ipsa optio repellat voluptas consectetur voluptatem fugit earum mollitia, nisi accusantium corporis adipisci neque libero animi, est nesciunt esse?</p>
                                <div class="learn__more__container">
                                    <button class="learn__more">Learn More</button>    
                                </div>
                         
                            </div>
                        </div>
                        <div class="page__img__container">

                            <img class="react__img" src="./assets/hero-screenshot-1.40a097b525c2f8c9808e.png" alt="">
                        </div>
                    </div>
                </div>
            
        </section>
        
        <section>
            <div class="row">
                <div class="section__three">
                    <div class="img__wrapper--two">
                        <img class="shot__two" src="./assets/hero-screenshot-2.241aac1fbc66db29d873.png" alt="">
                    </div>
                    <div class="section__list">
                        <div class="section__content">              
                            <h5> <span class="text--purple">STEPS</h5></span>
                            <h2 class="started__container">Easy to <span class="text--purple"> Get Started</span></h2>
                            <ul class="steps__wrapper">
                                <li class="steps__list">
                                    <div class="number__list--container">
                                        01
                                    </div>
                                    <div class="number__list">
                                        <h6 class="register__container">Register</h6>
                                        <p class="para__container">Create an account with us using Google or Facebook</p>
                                    </div>
                                </li>
                                
                                <li class="steps__list">
                                    <div class="number__list--container">
                                        02
                                    </div>
                                    <div class="number__list">
                                        <h6 class="register__container">Download</h6>
                                        <p class="para__container">Browse and Download the template that you like from the marketplace</p>
                                    </div>
                                </li>
                                
                                <li class="steps__list">
                                    <div class="number__list--container">
                                        03
                                    </div>
                                    <div class="number__list">
                                        <h6 class="register__container">Run</h6>
                                        <p class="para__container">Follow the instructions to setup and customize thetemplate to your needs</p>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        
        <div class="row">
            <div class="section__four">
                <div class="values__img__wrapper">
                    <img class="values__img" src="./assets/values__img.svg" alt="">
                </div>
                <div class="values__column__container">
                    <div class="values__column">
                        <h5><span class="text--purple">VALUES</span></h5>
                        <h2 class="values__title">We Always Abide by Our <span class="text--purple"> Principles. </span></h2>
                        <p class="values__para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae error, ipsa temporibus nihil fuga, omnis voluptate atque eaque quam laboriosam mollitia illum dolores hic sequi et sunt provident tenetur officiis.</p>
                        <div class="horizontal">
                            
                            
                            <div class="afford__container">
                                <div class="horizontal__afford">
                                    <div class="affordable__container">
                                        <div class="dollar__sign">
                                            <i class="fa-solid fa-dollar-sign"></i>
                                        </div>
                                        
                                        <div class="affordable">Affordable</div>
                                    </div>
                                    <div class="affordable__para"> We promise to offer you the best rate we can - at par with the industry standard.</div>
                                    
                                </div>
                                
                                
                                
    <div class="afford__container">
        <div class="horizontal__afford">
            <div class="affordable__container">
                
                <div class="dollar__sign">
                    <i class="fa-solid fa-bag-shopping"></i>
                </div>
                <div class="affordable">Professionalism</div>
            </div>
            <div class="affordable__para"> We promise to offer you the best rate we can - at par with the industry standard.</div>
        </div>
    </div>
</div>
<div class="learn__more__container--two">

    <button class="learn__more--two">Learn More</button>
</div>


</div>

</div>
</div>
</div>

</div>

</div>
</section>

<section>
    <div class="row">
        <div class="section__five">
            <div class="header__container">
                <h5 class="pricing__wrapper"><span class="text--purple">PRICING </span></h5>
                <h2>Reasonable & Flexible <span class="text--purple">Plans.</span></h2>
                <p class="header__para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia quam porro mollitia, eius quidem tenetur voluptas quisquam consectetur. Rerum, blanditiis amet. Quos atque accusantium sunt quisquam earum perferendis harum dicta.</p>
            </div>
            
            
            <div class="three__plans__container">
                <div class="three__plans__column">
                    
                    <div class="three__plans__highlight">
                    </div>
                    
                    <div class="price__plans__box">
                        <span class="headline">PERSONAL</span>
                        <span class="price">$17.99</span>
                        <span class="monthly">MONTHLY</span>
                    </div>
                    
                    <div class="features__wrapper">
                        
                        <span class="for">For Individuals</span>
                        <span class="feature">30 Templates</span>
                <span class="feature">7 Landing Pages</span>
                <span class="feature">12 Internal Pages</span>
                <span class="feature">Basic Assistance</span>
            </div>
            <div class="three__plans__button--wrapper">
                <button class="three__plans__button"> BUY NOW</button>
            </div>
        </div>
        
        <div class="three__plans__column-two">
            
            <div class="three__plans__highlight">
            </div>
            
            <div class="price__plans__box">
                <span class="headline">BUSINESS</span>
                <span class="price">$37.99</span>
                <span class="monthly">MONTHLY</span>
            </div>
            
            <div class="features__wrapper">
                
                <span class="for">For Small Businesses</span>
                <span class="feature">60 Templates</span>
                <span class="feature">15 Landing Pages</span>
                <span class="feature">22 Internal Pages</span>
                <span class="feature">Priority Assistance</span>
            </div>
            <div class="three__plans__button--wrapper">
                <button class="three__plans__button"> BUY NOW</button>
            </div>
        </div>
        
        
        
        <div class="three__plans__column">
            
            <div class="three__plans__highlight">
            </div>
            
            <div class="price__plans__box">
                <span class="headline">ENTERPRISE</span>
                <span class="price">$57.99</span>
                <span class="monthly">MONTHLY</span>
            </div>
            
            <div class="features__wrapper">
                
                <span class="for">For Large Companies</span>
                <span class="feature">90 Templates</span>
                <span class="feature">27 Landing Pages</span>
                <span class="feature">37 Internal Pages</span>
                <span class="feature">Personal Assistance</span>
            </div>
            <div class="three__plans__button--wrapper">
                <button class="three__plans__button"> BUY NOW</button>
            </div>
        </div>
        
        
        
    </div>
    
</div>


</section>
<section>
    <div class="row">
        <div class="test__container">
            <div class="two__section">
                <div class="img__test">
                    <img class="img__size" src="./assets/love-illustration.c759090fa833369ad6ffb6eb19cacb3e.svg" alt="">
                </div>
                <div class="client__column">
                    
                    <h5><span class="text--purple">TESTIMONIALS</span></h5>
                    <h2 class="clients__container">Our Clients <span class="text--purple"> Love Us.</span></h2>
                    <p class="client__header">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate ducimus dolore corporis laudantium fuga, neque quibusdam, debitis architecto delectus aspernatur amet, ad id soluta harum impedit eligendi similique iste nihil?
                    </p>
                    <div>
                        <div class="user__exp">
                            <div class="stars">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                            <h3>
                                Amazing User Experience
                            </h3>
                            <p class="user__exp__para">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit veniam sequi vitae fugit voluptate quia molestiae provident magnam, voluptatem doloremque velit cum. Vel eaque consequatur officia. Error, odio maxime. Enim molestiae quaerat earum eveniet ut ad dicta perspiciatis quae sunt.
                            </p>
                            <div class="hale__container">
                                <div class="hale__picture--mask">
                                    <img class="hale__picture" src="./assets/photo-1494790108377-be9c29b29330.avif" alt="">
                                  </div>
                                  <div class="hale__info">

                                      <h5 class="name__hale">Charolette Hale</h5>
                                      <p>Director, Delos Inc</p>
                                    </div>
                                    <div class="arrows">

<i class="fa-solid fa-arrow-right"></i>
<i class="fa-solid fa-arrow-right left__point"></i>
</div>

                                      
                            </div>
                            
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    
</section>
<section>
    <div class="row">
        <div class="section__seven">
            <div class="section__seven--container">
                <div class="section__seven--content">
                    <div class="developers__container">

                        <h5 class="developers">Developers all over the world are happily using Treact.</h5>
                    </div>
                        <div class="get__us">
                            <div class="get__us__container">

                                <a class="get__started" href="Get Started">Get Started</a>
                                <a class="contact__us" href="Contact Us">Contact Us</a>
                            </div>
                              
                         

                    </div>
                </div>
                

            </div>
            
        </div>
    </div>
</section>




</main>
<footer>
    <div class="row">
        <div class="footer__rows">
            <div class="footer__rows--container">
                
                <div class="footer__main">
                    <h5 class="main__tag">MAIN</h5>
                    <ul>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black"> Blog</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">FAQs</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Support</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">About Us</a>
                        </li>
                    </ul>
                </div>
                <div class="footer__main">
                    <h5 class="main__tag">PRODCUT</h5>
                    <ul>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black"> Log In</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Personal</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Business</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Team</a>
                        </li>
                    </ul>
                </div>
                <div class="footer__main">
                    <h5 class="main__tag">PRESS</h5>
                    <ul>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black"> Logos</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Events</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Stories</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Office</a>
                        </li>
                    </ul>
                </div>
                <div class="footer__main">
                    <h5 class="main__tag">TEAM</h5>
                    <ul>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black"> Career</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Founders</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Culture</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Onboarding</a>
                        </li>
                    </ul>
                </div>
                <div class="footer__main">
                    <h5 class="main__tag">LEGAL</h5>
                    <ul>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black"> GDPR</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Privacy</a>
                        </li>
                        <li>
                            
                            <a class="tags" href=""class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Terms of Service</a>
                        </li>
                        <li>
                            
                            <a class="tags" href="" class="
                            nav__link--anchor 
                            link__hover-effect 
                            link__hover-effect--black">Disclaimer</a>
                        </li>
                    </ul>
                </div>
             
             
                </div>
</div>
<div class="extra__space">

</div>




 <div class="footer__info">
                        <div class="treact__logo">
                            <img src="./assets/logo-light.d9a5d1b5be5ea077b26864fdfc2e96a4.svg" class="logo" alt=""> <h5 class="treact__inc">Treact Inc.</h5>
                        </div> 
                       <p> © 2018 Treact Inc. All Rights Reserved</p>
                       <div class="socials">
                        <i class="fa-brands fa-facebook"></i>


                       </div>
                        </div>
              
                    
                </div>
            </div>
            
        </div>
    </div>
    
</footer>
</div>
</div>


</body>
</html>
