<script>
  import cloud_orange_new from './assets/cloud_orange_new.png';
  import cloud_green_new from './assets/cloud_green_new.png';
  import cloud_pink_new from './assets/cloud_pink_new.png';
  import cloud_grey_new from './assets/cloud_grey_new.png';
  import arrow from './assets/arrow.png';
  import bjorkafrihet from './assets/bjorkafrihet.png';
  import yrgoLogo from './assets/yrgo-logo.png';
  import bjorkaLogo from './assets/bjorka-logo.png';
  import greenLogo from './assets/green-logo.png';
  import goldLogo from './assets/gold-logo.png';
  import redLogo from './assets/red-logo.png';
  import redRec from './assets/red-rec.png';
  import greenRec from './assets/green-rec.png';
  import goldRec from './assets/gold-rec.png';
  import elin from './assets/elin.png';
  import sofia from './assets/sofia.png';
  import eric from './assets/eric.png';
  import vilma from './assets/vilma.png';
  import luis from './assets/luis.png';
  import Game from './lib/Game.svelte';
  import Mobile from './assets/mobile.png';
  import GameLogoGreen from './assets/green-game-logo.png';
  import GameLogoRed from './assets/red-game-logo.png';

  let src = GameLogoGreen;

  function handleMouseOver(e) {
    src = GameLogoRed;
  }
  function handleMouseOut(e) {
    src = GameLogoGreen;
  }
</script>

<nav>
  <ul>
    <li>
      <a class="game-logo-container" href="#header"
        ><img
          {src}
          class="game-logo"
          alt="Game logo"
          on:focus={handleMouseOver}
          on:mouseover={handleMouseOver}
          on:blur={handleMouseOut}
          on:mouseout={handleMouseOut}
        /></a
      >
    </li>
    <li><a href="#game">Spela</a></li>
    <li><a href="#store">Gör skillnad</a></li>
    <li><a href="#about">Om oss</a></li>
  </ul>
</nav>

<main class="scroller">
  <section id="header" class="header">
    <div class="header-cloud-div-orange">
      <img
        class="header-cloud header-cloud-orange"
        src={cloud_orange_new}
        alt="Decorative orange cloud"
      />
    </div>
    <div class="header-text">
      <h1>Hinner du med i trendcyklerna?</h1>
      <h2>
        Vet du vad Y2K är? Eller Dark Academia? Trendcyklerna blir allt
        snabbare, vilket betyder fler obegripliga koncept och mer produktion av
        nya kläder. I det här spelet är målet är att sortera kläder som skänkts
        till en second hand-butik. Hur många plagg hinner du med?
      </h2>
      <a href="#game"
        ><img class="arrow" src={arrow} alt="Arrow down symbol" /></a
      >
    </div>
    <div>
      <div class="header-cloud-div-green">
        <img
          class="header-cloud header-cloud-green"
          src={cloud_green_new}
          alt="Decorative green cloud"
        />
      </div>
    </div>
    <div>
      <div class="header-cloud-div-pink">
        <img
          class="header-cloud header-cloud-pink"
          src={cloud_pink_new}
          alt="Decorative pink cloud"
        />
      </div>
    </div>
  </section>

  <section id="game" class="game">
    <div>
      <Game />
    </div>
  </section>

  <section class="game-info">
    <div class="game-info-div">
      <div class="red-div">
        <img class="background-info" src={redRec} alt="Red background" />
        <div class="text-logo">
          <h3>Butik</h3>
          <p>
            Till butiken sorteras det som är helt och rent. På så sätt kan det
            enkelt säljas vidare, vilket förlänger plaggets livslängd betydligt.
          </p>
          <img class="logo" src={redLogo} alt="Red logo" />
        </div>
      </div>
      <div class="gold-div">
        <img class="background-info" src={goldRec} alt="Gold background" />
        <div class="text-logo">
          <h3>Trend</h3>
          <p>
            Du vet väl att mode alltid går i cykler? Allt som finns i butikerna
            idag har på något sätt redan existerat, så second hand i första
            hand!
          </p>
          <img class="logo" src={goldLogo} alt="Gold logo" />
        </div>
      </div>
      <div class="green-div">
        <img class="background-info" src={greenRec} alt="Green background" />
        <div class="text-logo">
          <h3>Återvinning</h3>
          <p>
            I Sverige slänger vi i snitt hela 7,5 kilo textil per person i
            soporna varje år! Skänk eller sortera istället dina gamla kläder.
          </p>
          <img class="logo" src={greenLogo} alt="Green logo" />
        </div>
      </div>
      <div />
    </div>
  </section>

  <section id="store" class="stores">
    <div class="div-grey-cloud">
      <img
        class="store-cloud-grey"
        src={cloud_grey_new}
        alt="Decorative grey cloud"
      />
    </div>
    <div class="store-cloud-div-pink">
      <img
        class="store-cloud-pink"
        src={cloud_pink_new}
        alt="Decorative pink cloud"
      />
    </div>
    <div class="gor-skillnad">
      <h2>Gör skillnad</h2>
      <img src={bjorkafrihet} alt="Björkå Frihet logo" />
      <h4>
        Bryt dig loss ifrån ohållbara trendcykler och hitta din egen personliga
        stil! Det är bättre både för dig, planeten och plånboken.
      </h4>
      <button
        ><a
          href="https://bjorkafrihet.se/oppettider-bjorkafrihet-second-hand-butiker/"
          target="_blank">Hitta butik</a
        ></button
      >
    </div>
  </section>

  <section id="about" class="about">
    <h2>Om oss</h2>
    <div class="div-orange-cloud">
      <img
        class="about-cloud-orange"
        src={cloud_orange_new}
        alt="Decorative orange cloud"
      />
    </div>
    <div class="div-green-cloud">
      <img
        class="about-cloud-green"
        src={cloud_green_new}
        alt="Decorative green cloud"
      />
    </div>
    <div class="profiles">
      <div class="profile-container">
        <div class="profile-image-div">
          <img src={elin} alt="Profile picture" />
        </div>
        <div class="profile-text-div">
          <a
            href="mailto:elin.deninger@gmail.com
          ">Elin Deninger, UX22 📩</a
          >
          <p>
            Lett idégenerering och designprocess. Designat UI för spel samt UI
            för hemsida. Utformat och genomfört användartester för samtliga.
          </p>
        </div>
      </div>
      <div class="profile-container">
        <div class="profile-image-div">
          <img src={eric} alt="Profile picture" />
        </div>
        <div class="profile-text-div">
          <a
            href="mailto:erlo1129@hotmail.com
          ">Eric Locher, GP21 📩</a
          >
          <p>
            Programmerat gameplay samt system. Vart delaktig i utformning av
            spelidé och mer konkreta gameplay koncept.
          </p>
        </div>
      </div>
      <div class="profile-container">
        <div class="profile-image-div">
          <img src={luis} alt="Profile picture" />
        </div>
        <div class="profile-text-div">
          <a
            href="mailto:luisgvecchio@gmail.com
          ">Luis Pablo Gomez Vecchio, GP21 📩</a
          >
          <p>
            Programmerat spels gameplay, genomfört UI och menyer och skapat
            spels musik.
          </p>
        </div>
      </div>
      <div class="profile-container">
        <div class="profile-image-div">
          <img src={sofia} alt="Profile picture" />
        </div>
        <div class="profile-text-div">
          <a href="mailto:sofia@ronnkvist.com">Sofia Rönnkvist, WU21 📩</a>
          <p>
            Idéutformning av koncept för hemsida och spel, utveckling av hela
            hemsidan samt dess copywriting.
          </p>
        </div>
      </div>
      <div class="profile-container">
        <div class="profile-image-div">
          <img src={vilma} alt="Profile picture" />
        </div>
        <div class="profile-text-div">
          <a
            href="mailto:vilma_gustafsson@outlook.com
          ">Vilma Gustafsson, GA21 📩</a
          >
          <p>
            Utformning av idé för spelkoncept. Skapat grafik för assets i spel
            samt till hemsida.
          </p>
        </div>
      </div>
      <div class="bottom-logos">
        <a href="http://yrgo.se/" target="_blank"
          ><img src={yrgoLogo} alt="Yrgo logo" /></a
        >
        <a href="https://bjorkafrihet.se/" target="_blank">
          <img src={bjorkaLogo} alt="Björkå Frihet logo" /></a
        >
      </div>
    </div>
  </section>
</main>

<style>
</style>
