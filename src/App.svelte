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
  import vite from './assets/vite.svg';
</script>

<nav>
  <ul>
    <li><a href="#logo">Namn</a></li>
    <li><a href="#game">Spela</a></li>
    <li><a href="#store">Gör skillnad</a></li>
    <li><a href="#about">Om oss</a></li>
  </ul>
</nav>

<main class="scroller">
  <section class="header">
    <div class="header-cloud-div-orange">
      <img
        class="header-cloud header-cloud-orange"
        src={cloud_orange_new}
        alt="Decorative orange cloud"
      />
    </div>
    <div class="header-text">
      <h1>Hinner du med i trendcykeln?</h1>
      <h2>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris.
      </h2>
      <img class="arrow" src={arrow} alt="Arrow down symbol" />
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
  </section>

  <section id="game" class="game">
    <div>
      <h2>Spelet</h2>
    </div>
  </section>

  <section class="game-info">
    <div class="game-info-div">
      <div class="red-div">
        <img class="background-info" src={redRec} alt="Red background" />
        <div class="text-logo">
          <h3>Lorem ipsum</h3>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img class="logo" src=" red-logo.png" alt="Red logo" />
        </div>
      </div>
      <div class="gold-div">
        <img
          class="background-info"
          src={goldRec}
          alt="Gold background"
        />
        <div class="text-logo">
          <h3>Lorem ipsum</h3>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img class="logo" src={goldLogo} alt="Gold logo" />
        </div>
      </div>
      <div class="green-div">
        <img
          class="background-info"
          src={greenRec}
          alt="Green background"
        />
        <div class="text-logo">
          <h3>Lorem ipsum</h3>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img class="logo" src={greenLogo} alt="Green logo" />
        </div>
      </div>
      <div />
    </div>
  </section>

  <section id="store" class="stores">
    <div>
      <h2>Gör skillnad</h2>
      <img src={bjorkafrihet} alt="Björkå Frihet logo" />
      <h4>
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.
      </h4>
      <button>Hitta butik</button>
      <img src="#" alt="" />
      <img src="#" alt="" />
      <img src="#" alt="" />
    </div>
  </section>

  <section id="about" class="about">
    <h2>Om oss</h2>
    <div>
      <div>
        <div>
          <img src="" alt="" />
        </div>
        <div>
          <h3>Namn Efternam, Klassnamn</h3>
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>
    </div>
  </section>
</main>

<footer>
  <img src={yrgoLogo} alt="Yrgo logo" />
  <img src={bjorkaLogo} alt="Björkå Frihet logo" />
</footer>

<style>
</style>
