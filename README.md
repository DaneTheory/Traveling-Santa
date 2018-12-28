<style>
  html {
    font-size: 100%;
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: "Helvetica", sans-serif;
    -webkit-font-smoothing: antialiased;
    line-height: 1.31;
  }
  .r-logo {
    width: 3rem;
    margin: -1rem 1rem -2rem 0rem;
  }
  .title {
    position: absolute;
    font-size: 2.2em;
    font-weight: bold;
    width: 100%;
    text-transform: uppercase;
    color: white;
    text-shadow: 1px 2px 3px rgba(0,0,0,0.65);
  }
  .sub-title {
    position: absolute;
    font-size: 0.8rem;
    margin-left: 0.5rem;
    margin-top: 3.3rem;
    color: white;
    opacity: 0.6;
  }
  .top-sky {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    z-index: -1;
    height: 0;
    padding-bottom: 28.6%;
  }
  .top-sky__bg {
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    max-height: 700px;
  }
  .top-sky__stars {
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    max-height: 700px;
  }
  .top-sky__globe {
    max-height: 27.7%;
    max-width: 180px;
    position: absolute;
    top: 40%;
    right: 15%;
    transform: translate(50%, -50%);
  }
  .top-sky__santa {
    max-height: 78.4%;
    max-width: 481px;
    width: 42%;
    position: absolute;
    top: 40%;
    right: 15%;
    transform-origin: 48.97% 50%;
    transform: translate(50%, -50%);
    animation-name: spinner;
    animation-duration: 7s;
    animation-iteration-count: infinite;
    animation-timing-function: cubic-bezier(0.92, 0.48, 0.73, 0.85);
  }
  .overview {
    padding-top: 2rem;
    padding-left: 5rem;
    padding-right: 5rem;
    color: white;
    text-shadow: 0px 1px 1px rgba(0,0,0,1);
  }
</style>

<div class="header">
  <svg class="r-logo" width="100" height="100" viewBox="0 0 22 30" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <title>R</title>
      <path id="R" d="M9.15344737,13.4151346 L8.38576316,13.4151346 L8.38576316,15.5284038 L5.70060526,15.5284038 L5.70060526,9.81167308 L8.38576316,9.81167308 L8.38576316,5.90071154 L9.15344737,5.90071154 C11.9775526,5.90071154 13.7190263,7.65975 13.7190263,9.66398077 C13.7190263,11.6676346 11.9775526,13.4151346 9.15344737,13.4151346 Z M14.3107105,17.6716731 C17.3484474,16.1791731 19.4152895,13.5709038 19.4152895,9.39225 C19.4152895,3.98878846 14.5920789,-5.76923077e-05 9.36765789,-5.76923077e-05 L8.38576316,-5.76923077e-05 L8.38576316,4.16763462 L-0.000289473684,4.16763462 L-0.000289473684,29.9999423 L5.70060526,29.9999423 L5.70060526,20.7016731 L9.26228947,20.7016731 L14.7773421,29.9849423 L21.5649211,29.9849423 L14.3107105,17.6716731 Z" fill="#FC5F71">
    </path>
  </svg>
  <e class="title">Traveling Santa</e>
  <span>
    <i class="sub-title">Ho ho holy smokes, Santa is in dire need of your help!</i>
  </span>
</div>

<div class="top-sky">
      <svg class="top-sky__bg" viewBox="0 0 1440 1400" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="none">
        <g transform="translate(0 -248)" class="top-sky__bg--inner">
        <path d="M963.30318,0.0426426558 C913.364939,6.67586139 845.168458,28.5839942 814.193091,96.4772475 C762.305116,210.203487 876.882191,233.620225 838.140868,329.915436 C801.707594,420.473748 675.826407,395.757495 642.564731,520.124913 C609.303804,644.492331 570.054996,660.453724 466.280546,661.783965 C400.297662,662.629324 355.831571,722.086226 332.194132,765.281962 C332.194132,765.281962 289.349447,824.042643 286.351009,916.972156 C283.352571,1009.90167 212.139661,1081.8471 130.432217,1077.35051 C48.7247725,1072.85392 0.000149921916,1176.27548 0.000149921916,1176.27548 L0.000149921916,1647.99993 C48.8199729,1646.11061 52.6025029,1562.99715 83.5816179,1480.94039 C104.041462,1426.74749 131.024408,1395.81471 143.774517,1383.31344 C176.204877,1355.12507 214.391488,1336.66057 258.615454,1337.40326 C437.022534,1340.40099 521.728416,1344.89758 595.190155,1227.23682 C668.651894,1109.57607 754.107386,1003.15679 885.289062,1014.39826 C1016.47074,1025.63973 1281.83253,1084.84483 1439.62535,809.428727 L1439.62535,730.935514 L1439.62535,0.0426426558 L963.30318,0.0426426558 Z" fill="#532C54"></path>
        </g>
      </svg>
      <img src="https://traveling-santa.reaktor.com/assets/images/stars.svg" class="top-sky__stars rellax" data-rellax-speed="2.5" style="transform: translate3d(0px, 0px, 0px);">
      <img src="https://traveling-santa.reaktor.com/assets/images/globe.svg" class="top-sky__globe">
      <img src="https://traveling-santa.reaktor.com/assets/images/pukki.svg" class="top-sky__santa">
    </div>

<div class="overview">

Our planet is warming up at an alarming pace, and Santa is fervently looking for ways to cut down on CO2 emissions. The red man is acutely aware of the carbon footprint galloping around the world at turbo speed generates, and has made it his mission to find a more sustainable way to bring delight and joy to families around the world.

You have until the 31st of December 2018.

<br></br>

__Complete Details:__ [Traveling Santa - original source][1]

</div>

---



## Installation

* Clone this repo and then ```cd``` into the project directory

```bash
git clone https://github.com/DaneTheory/traveling-santa.git
```



[1]: https://traveling-santa.reaktor.com/?fbclid=IwAR17tSG876Thbf9oenl1exO5WeFRpJeVEOSKJEAclg355uyWlEX0Q-l6_YI
