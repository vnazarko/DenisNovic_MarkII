<script>

</script>

<template>
  <header id="home">
      <div class="container">
          <nav class="nav  wow animate__animated  animate__fadeInDown">
              <ul class="header__nav-list">
                  <li class="nav-list__link"><a href="#home">Home</a></li>
                  <li class="nav-list__link"><a href="#about">About me</a></li>
                  <li class="nav-list__link"><a href="#skills">Skills</a></li>
                  <li class="nav-list__link"><a href="#portfolio">Portfilio</a></li>
                  <li class="nav-list__link"><a href="#contacts">Contacts</a></li>
              </ul>
          </nav>
          <div class="burger">
              <span></span>
          </div>
      </div>
  </header>
  <main class="intro">
        <div class="container">
            <div class="intro__text-block">
                <h1 class="intro_text-block__title  wow animate__animated  animate__fadeInLeft">Denis Novic</h1>
                <h3 class="intro_text-block__subtitle  wow animate__animated  animate__fadeInRight">UX | UI designer  24 yars old, Minsk</h3>
            </div>
            <div class="intro__img  wow animate__animated  animate__fadeInRight"></div>
        </div>
  </main>
  <section class="about" id="about">
      <div class="container">
          <h1 class="about__title  wow animate__animated  animate__fadeInLeft">About me</h1>
          <p class="about__text  wow animate__animated  animate__fadeInRight">
              Hi, I'm Denis - UX/UI designer from Minsk.
              I'm interested in design and everything connected with it.
          </p>
          <p class="about__text  wow animate__animated  animate__fadeInLeft">
              I'm studying at courses "Web and mobile design
              "interfaces" in IT-Academy.
          </p>
          <p class="about__text  wow animate__animated  animate__fadeInRight">
              Ready to implement excellent projects
              with wonderful people.
          </p>
      </div>
  </section>
  <section class="skills" id="skills">
      <div class="container">
          <h1 class="skills__title  wow animate__animated  animate__fadeInLeft">Skills</h1>
          <p class="skills__subtitle  wow animate__animated  animate__fadeInRight">I work in sech programs as</p>
          <div class="skills__programms">
              <div class="programms__prog-cart  wow animate__animated  animate__fadeInDown">
                  <img src="/src/assets/img/skills/photoshop.png" alt="Adobe Photoshop" class="programms_prog-cart__icon">
                  <h2 class="programms_prog-cart__title">Adobe Photoshop</h2>
                  <img src="/src/assets/img/skills/fourSt.svg" alt="Four Stars" class="programms_prog-cart__stars">
              </div>
              <div class="programms__prog-cart  wow animate__animated  animate__fadeInUp">
                  <img src="/src/assets/img/skills/illustrator.png" alt="Adobe Illustator" class="programms_prog-cart__icon">
                  <h2 class="programms_prog-cart__title">Adobe Illustrator</h2>
                  <img src="/src/assets/img/skills/threeSt.svg" alt="Three Stars" class="programms_prog-cart__stars">
              </div>
              <div class="programms__prog-cart  wow animate__animated  animate__fadeInDown">
                  <img src="/src/assets/img/skills/AfEffects.png" alt="Adobe After Effects" class="programms_prog-cart__icon">
                  <h2 class="programms_prog-cart__title">Adobe After Effects</h2>
                  <img src="/src/assets/img/skills/fourSt.svg" alt="Four Stars" class="programms_prog-cart__stars">
              </div>
              <div class="programms__prog-cart  wow animate__animated  animate__fadeInUp">
                  <img src="/src/assets/img/skills/Figma.png" alt="Figma" class="programms_prog-cart__figma">
                  <h2 class="programms_prog-cart__title">Figma</h2>
                  <img src="/src/assets/img/skills/fourSt.svg" alt="Four Stars" class="programms_prog-cart__stars">
              </div>
          </div>
      </div>
  </section>
  <section class="portfolio" id="portfolio">
      <div class="container">
          <h1 class="portfolio__title  wow animate__animated  animate__fadeInLeft">Portfolio</h1>
          <div class="portfolio__sites">
              <div class="portfolio__site-cart">
                  <img src="/src/assets/img/portfolio/levis.png" alt="" class="portfolio_site-cart__img  wow animate__animated  animate__fadeInRight">
                  <a href="#" class="portfolio_ste-cart__text  wow animate__animated  animate__fadeInDown">Online fashion store - Homepage</a>
              </div>
              <div class="portfolio__site-cart"> 
                  <img src="/src/assets/img/portfolio/reebok_web.png" alt="" class="portfolio_site-cart__img  wow animate__animated  animate__fadeInLeft">
                  <a href="#" class="portfolio_ste-cart__text  wow animate__animated  animate__fadeInDown">Reebok Store - Concept</a>
              </div>
              <div class="portfolio__site-cart">
                  <img src="/src/assets/img/portfolio/braun.png" alt="" class="portfolio_site-cart__img  wow animate__animated  animate__fadeInRight">
                  <a href="#" class="portfolio_ste-cart__text  wow animate__animated  animate__fadeInDown">Braun Landing Page - Concept</a>
              </div>
          </div>
      </div>
  </section>
  <footer class="footer" id="contacts">
      <div class="container">
          <h1 class="footer__title  wow animate__animated  animate__fadeInLeft">Contact</h1>
          <h2 class="footer__subtitle  wow animate__animated  animate__fadeInRight">Want to know more or just chat?  You are welcome!</h2>
          <a href="#" class="footer__btn  wow animate__animated  animate__fadeInLeft">Send message</a>
          <div class="footer__social">
              <img src="/src/assets/img/footer/linkedln.svg" alt="" class="social__icon  wow animate__animated  animate__fadeInUp">
              <img src="/src/assets/img/footer/inst.svg" alt="" class="social__icon  wow animate__animated  animate__fadeInDown">
              <img src="/src/assets/img/footer/behance.svg" alt="" class="social__icon  wow animate__animated  animate__fadeInUp">
<!--              <img src="/src/assets/img/footer/surface1%207.svg" alt="" class="social__icon">-->
          </div>
      </div>
  </footer>
</template>

<style lang="scss">
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

  @font-face {
      src: url("/src/assets/fonts/Gilroy/Gilroy-Bold.woff2") format('woff2');
      font-family: 'Gilroy';
      font-weight: 700;
  }

  @font-face {
      src: url("/src/assets/fonts/Gilroy/Gilroy-Medium.woff2") format('woff2');
      font-family: 'Gilroy';
      font-weight: 500;
  }

  body {
      max-width: 100%;
  }

  .container {
      width: 945px;
      margin: 0 auto;
  }

  @media (max-width: 1279px) {
      .container {
          width: 700px;
      }
  }
  @media (max-width: 767px) {
      .container {
          width: 480px;
      }
  }
  @media (max-width: 479px) {
      .container {
          width: 313px;
      }
  }


  .header {
      width: 100%;
      height: 88px;
      .container {
          height: 100%;
          display: flex;
          align-items: center;
      }
  }

  .header__nav-list {
      list-style-type: none;
      width: 100%;
      padding-bottom: 20px;
      border-bottom: 1px solid #828282;
      padding-top: 15px;
      display: flex;
      justify-content: space-between;
      flex-direction: row;
  }

  .nav-list__link {
      font-family: 'Gilroy';
      font-weight: bold;
      font-size: 18px;
      a {
          color: #828282;
          text-decoration: none;
          &:hover {
              color: #000;
              transition: all .3s;
          }
      }
  }

  .open{
      display: flex !important;
  }

  .nav ul{
      width: 100%;
      list-style: none;
      display: flex;
      justify-content: space-between;
  }

  .burger{
      display: none;
      position: relative;
      z-index: 50;
      align-items: center;
      justify-content: flex-end;
      width: 33px;
      height: 19px;
      margin-top: 66px;
      margin-left: 90%;
  }

  .burger span{
      height: 3px;
      width: 100%;
      transform: scale(1);
      background-color: #000;
  }

  .burger::before, .burger::after{
      content: '';
      position: absolute;
      height: 3px;
      width: 100%;
      background-color: #000;
      transition: all 0.3s ease 0s;
  }

  .burger::before { top: 0 }

  .burger::after { bottom: 0 }

  .burger.active span { transform: scale(0) }

  .burger.active::before{
      top: 50%;
      transform: rotate(-45deg) translate(0, -50%);
  }

  .burger.active::after{
      bottom: 50%;
      transform: rotate(45deg) translate(0, 50%);
  }

  @media (max-width: 767px) {

      .burger { display: flex }

      .nav{
          display: none;
          flex-direction: column;
          position: fixed;
          height: 100%;
          width: 100%;
          top: 66px; bottom: 0; left: 0; right: 28px;
          z-index: 50;
          overflow-y: auto;
          padding: 50px 40px;
          background-color:  #fff;
          border-bottom: none;
          animation: burgerAnimation 0.4s;
      }

      .header__nav-list {
          border-bottom: 1px solid #fff;
      }

      .nav ul{
          flex-direction: column;
          row-gap: 30px;
      }

      .nav-list__link {
          font-size: 34px;
      }
  }

  @keyframes burgerAnimation {
      from {opacity: 0}
      to {opacity: 1}
  }


  .intro {
      width: 100%;
      margin-top: 40px;
  }

  .intro__text-block {
      width: 61%;
      display: flex;
      justify-content: space-between;
      align-items: end;
  }

  .intro_text-block__title {
      font-size: 47px;
      font-family: 'Gilroy';
      font-weight: 700;
      color: #070707;
      width: 123px;
  }

  .intro_text-block__subtitle {
      font-size: 18px;
      font-family: 'Gilroy';
      font-weight: 500;
      color: #070707;
      width: 155px;
      margin-bottom: 10px;
  }

  .intro__img {
    content: url("/src/assets/img/intro/human.png");
    object-fit: cover;
    width: 100%;
    height: 387px;
    margin-top: 50px;
    margin-bottom: 104px;
  }

  @media (max-width: 1279px) {
    .intro__text-block {
      width: 80%;
    }
  }
  @media (max-width: 767px) {
    .intro__text-block {
      width: 90%;
    }
  }
  @media (max-width: 479px) {
    .intro__text-block {
      display: flex;
      flex-direction: column;
      row-gap: 23px;
      justify-content: flex-end;
      h3 {
        text-align: right;
      }
    }

    .intro__img {
      content: url("assets/img/intro/humanForMobile.png");
      object-fit: cover;
      height: 478px;
      margin-bottom: 83px;
    }
  }

  .about {
    width: 100%;
    height: 506px;
    background-color: #F6F6F6;
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      row-gap: 25px;
    }
  }

  .about__title {
    font-size: 34px;
    font-family: 'Gilroy';
    font-weight: 700;
    color: #070707;
    margin-top: 120px;
  }

  .about__text {
    font-size: 18px;
    font-family: 'Gilroy';
    font-weight: 500;
    color: #070707;
    width: 485px;
    text-align: center;
  }
  
  @media (max-width: 479px) {
    .about__text {
      width: 316px;
    }
  }

  .skills {
      width: 100%;
      height: 610px;
      .container {
          display: flex;
          justify-content: center;
          align-items: center;
          flex-direction: column;
          row-gap: 70px;
      }
  }

  .skills__title {
      font-family: 'Gilroy';
      font-weight: 700;
      font-size: 34px;
      color: #070707;
      margin-top: 90px;
  }

  .skills__subtitle {
      font-family: 'Gilroy';
      font-weight: 500;
      font-size: 18px;
      color: #070707;
  }

  .skills__programms {
      width: 100%;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      .programms__prog-cart {
          width: 166px;
          height: 206px;
          display: flex;
          justify-content: center;
          flex-direction: column;
          .programms_prog-cart__icon {
              width: 89px;
              height: 88px;
              object-fit: cover;
              margin-right: auto;
              margin-left: auto;
              margin-bottom: 24px;
          }
          .programms_prog-cart__figma {
              width: 59px;
              height: 88px;
              object-fit: cover;
              margin-right: auto;
              margin-left: auto;
              margin-bottom: 40px;
          }
          .programms_prog-cart__title {
              font-size: 14px;
              font-family: 'Gilroy';
              font-weight: 700;
              color: #828282;
              text-align: center;
              width: 80px;
              margin-right: auto;
              margin-left: auto;
              margin-bottom: 40px;
          }
      }
  }

  @media (max-width: 1279px) {
      .programms__prog-cart {
          margin: 0 auto 80px auto;
      }

      .programms_prog-cart__stars {
          width: 140px;
      }
  }
  @media (max-width: 767px) {
      .skills {
          height: 850px;
      }
  }
  @media (max-width: 479px) {
      .skills {
          height: 1410px;
      }
  }


  .portfolio {
      width: 100%;
      padding-top: 113px;
      padding-bottom: 80px;
      background-color: #F6F6F6;
      .container {
          display: flex;
          justify-content: center;
          align-items: center;
          flex-direction: column;
          row-gap: 47px;
      }
  }

  .portfolio__title {
      font-family: 'Gilroy';
      font-weight: 700;
      font-size: 34px;
      color: #070707;
  }

  .portfolio__sites {
      width: 100%;
      display: flex;
      flex-direction: column;
      row-gap: 100px;
  }

  .portfolio__site-cart {
      display: flex;
      flex-direction: column;
      row-gap: 49px;
  }

  .portfolio_ste-cart__text {
      font-size: 18px;
      font-family: 'Gilroy';
      font-weight: 500;
      color: #070707;
      text-align: center;
  }


  .footer {
      width: 100%;
      .container {
          padding-top: 114px;
          padding-bottom: 170px;
      }
  }

  .footer__title {
      font-family: 'Gilroy';
      font-weight: 700;
      font-size: 34px;
      color: #070707;
      text-align: center;
  }

  .footer__subtitle {
      font-family: 'Gilroy';
      font-weight: 500;
      font-size: 18px;
      color: #070707;
      width: 275px;
      text-align: center;
      margin: 20px auto 30px auto;
  }

  .footer__btn {
      font-family: 'Gilroy';
      font-weight: 700;
      font-size: 18px;
      color: #fff;
      text-decoration: none;
      background-color: #070707;
      border-radius: 25px;
      width: 180px;
      height: 42px;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 auto 0 auto;
      transition: all .3s;
      &:hover {
          color: #070707;
          background: none;
          border: 5px solid #070707;
          transition: all .3s;
      }
  }

  .footer__social {
      width: 342px;
      height: 40px;
      display: flex;
      justify-content: space-between;
      margin: 85px auto 0 auto;
  }

</style>
