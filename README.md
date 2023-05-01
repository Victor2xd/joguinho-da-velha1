<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">

  <title>X&O</title>
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }


    .landscap {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #000;
      overflow: hidden;
      display: none;


    }

    .vwio {
      height: 200px;
      width: 200px;
      border-radius: 50%;
      position: relative;
      animation: anm 3s infinite linear;
    }

    .f {
      position: absolute;
      width: 50%;
      height: 100%;
      border-top-left-radius: 200px;
      border-bottom-left-radius: 200px;
      background: linear-gradient(to top, #000, #8891E9 90%);

    }

    .d {
      position: absolute;
      width: 50%;
      height: 100%;
      border-top-right-radius: 200px;
      border-bottom-right-radius: 200px;
      background: linear-gradient(to bottom, #000, red 90%);
      right: 0%;
    }

    .gho {
      position: absolute;
      width: 90%;
      height: 90%;
      top: 10px;
      left: 10px;
      border-radius: 50%;
      background: black;
    }

    @keyframes anm {
      0% {
        transform: rotatez(0deg);
      }

      100% {
        transform: rotatez(360deg);
      }
    }

    .f::after {
      content: 'x';
      position: absolute;
      width: 20px;
      height: 20px;
      font-size: 50px;
      font-weight: 1000;
      color: #8891E9;
      top: -27.5px;
      right: -12.5px;
      z-index: 2;
      border-radius: 50%;
      text-shadow:
        0px 0px 10px #8891E9,
        0px 0px 40px #8891E9,
        0px 0px 60px #8891E9;
    }

    .d::after {
      content: 'O';
      position: absolute;
      width: 20px;
      height: 20px;
      font-size: 50px;
      font-weight: 1000;
      color: red;
      bottom: 12.5px;
      left: -25px;
      z-index: 2;
      border-radius: 50%;
      text-shadow:
        0px 0px 10px red,
        0px 0px 40px red,
        0px 0px 60px red;

    }

    .tix {
      position: absolute;
      color: white;
    }

    .tix span {
      color: red;
      text-shadow: 0px 0px 10px red;
    }

    .ghf {
      width: 100%;
      height: 100%;
      position: relative;
      left: 6%;
      bottom: 45px;

    }

    .conener {
      width: 100%;
      height: 100vh;
      background: #000;
      overflow: hidden;
    }

    .h {
      width: 28%;
      height: 23%;
      background: wh;
      position: relative;
      margin: .6%;
      font-size: 25vw;
      font-weight: 400;
      float: left;


    }

    .ll {
      height: 12%;
      width: 90%;
      background: transparent;
      border: snow .5vw solid;
      border-radius: 5vw;
      display: flex;
      text-align: center;
      justify-content: center;
    }

    .sp {
      color: #BAFFFF;
      font-size: 10vw;
      position: absolute;
      top: 11vh;
      text-transform: uppercase;
      font-weight: 800;
    }

    @keyframes opacit {
      0% {
        opacity: 1;
      }

      60% {
        opacity: 0;
      }

      100% {
        opacity: 0;
      }
    }

    .xx {
      background: transparent;
      border: #8891E9 .5vw solid;
      color: #8891E9;
      width: 10%;
      height: 10vh;
      border-radius: 10%;
      position: relative;
      float: left;
      display: flex;
      justify-content: center;
      align-items: center;
      right: 35%;
      top: 7%;
      font-size: 4vw;
    }

    .xxx {
      color: white;

    }

    .oo {
      background: transparent;
      color: red;
      border: red .5vw solid;
      width: 10%;
      height: 10vh;
      border-radius: 10%;
      float: right;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      left: 35%;
      top: 7%;
      font-size: 4vw;

    }

    .ooo {
      color: white;
    }

    .g {
      width: 85%;
      height: 70px;
      position: relative;
      top: -50px;
    }


    .ncli {
      width: 100%;
      height: 99vh;
      background: transparent;
      position: absolute;
      right: 0px;
      top: 0px;
      display: none;
    }

    @keyframes ef {
      0% {
        color: red;
        background: transparent;
      }

      20% {
        color: black;
        background: red;
      }

      80% {
        color: black;
        background: red;
      }

      100% {
        color: red;
        background: transparent;
      }
    }

    @keyframes eef {
      0% {
        color: #8891E9;
        background: transparent;
      }

      20% {
        color: black;
        background: #8891E9;
      }

      80% {
        color: black;
        background: #8891E9;
      }

      100% {
        color: #8891E9;
        background: transparent;
      }

    }

    .tt {
      position: absolute;
      width: 87%;
      height: 71%;
      display: flex;
      justify-content: center;
      align-items: center;

    }

    .t1 {
      position: absolute;
      width: 1vw;
      height: 100%;
      background: snow;
      left: calc(100%/3);
      border-radius: 100%;

    }

    .t2 {
      position: absolute;
      width: 1vw;
      height: 100%;
      background: snow;
      left: calc(100%/3*2);
      border-radius: 100%;

    }

    .t3 {
      position: absolute;
      height: 1vw;
      width: 100%;
      background: snow;
      top: calc(100%/3);
      border-radius: 100%;

    }

    .t4 {
      position: absolute;
      height: 1vw;
      width: 100%;
      background: snow;
      top: calc(100%/3*2);
      border-radius: 100%;
    }

    .drer {
      position: absolute;
      height: 100%;
      width: 100%;
      top: 100%;
      background: black;
      animation: eref 1s linear;
    }

    .drar {
      position: absolute;
      height: 100%;
      width: 100%;
      right: 100%;
      background: black;
      animation: ereff 1s linear;
    }

    @keyframes eref {
      0% {
        top: 0%;

      }

      100% {
        top: 100%;

      }
    }

    @keyframes ereff {
      0% {
        right: 0%;


      }

      100% {
        right: 100%;

      }
    }

    .xti {
      color: #8891E9;
      text-shadow: #8891E9 0 0 15px;

    }

    .oti {
      color: red;
      text-shadow: red 0 0 15px;
    }

    .n1 {
      position: absolute;
      background: snow;
      height: 3%;
      width: 90%;
      top: calc(100%/6 - 3%*.5);
      display: none;

    }

    .n2 {
      position: absolute;
      background: snow;
      height: 3%;
      width: 90%;
      top: calc(100%/2 - 3%*.5);
      display: none
    }

    .n3 {
      position: absolute;
      height: 3%;
      background: snow;
      width: 90%;
      bottom: calc(100%/6 - 3%*.5);
      display: none
    }

    .n4 {
      position: absolute;
      width: 3%;
      height: 90%;
      right: calc(100%/6 - 3%*.70);
      display: none
    }

    .n5 {
      position: absolute;
      width: 3%;
      background: snow;
      height: 90%;
      right: calc(100%/2 - 3%*.60);
      display: none
    }

    .n6 {
      position: absolute;
      width: 3%;
      background: snow;
      height: 90%;
      left: calc(100%/6 - 3%*.50);
      display: none
    }

    .n7 {
      position: absolute;
      width: 3%;
      background: snow;
      height: 90%;
      left: 50%;
      transform: skew(40deg);
      transition: 1s;
      display: none
    }

    .n8 {
      position: absolute;
      width: 3%;
      height: 90%;
      background: red;
      left: 50%;
      transform: skew(-40deg);
      display: none;


    }

    @keyframes n8 {
      0% {
        height: 0;
      }

      100% {
        height: 90%;
      }

    }

    @keyframes n7 {
      0% {
        height: 0;
      }

      100% {
        height: 90%;
      }

    }

    @keyframes n1 {
      0% {
        width: 0;

      }

      100% {
        width: 90%;

      }

    }

    @keyframes n2 {
      0% {
        height: 0;

      }

      100% {
        height: 90%;

      }

    }

    #option {
      position: relative;
      top: 3vh;
      background: transparent;
      color: snow;
      border: .5vw snow solid;
      height: 5vh;
      width: 20%;
      border-radius: 40px;
      right: -36%;
      margin-bottom: 4vh;
      font-size: 4vw;
    }

    .setting {
      margin-left: 10%;
      margin-top: 5%;
      width: 80%;
      height: 85%;
      background: linear-gradient(#8891E9, #9398CD);
      border: black 1px solid;
      position: absolute;
      top: 0;
      border-radius: 5%;
      z-index: 4;
      box-shadow: inset 1px 1px 1px 1px snow;
      display: none;
    }

    .cr {
      position: absolute;
      right: 4%;
      top: 2%;
      font-size: 5vh;
    }

    #restart {
      position: absolute;
      background: transparent;
      color: snow;
      border: 1vw snow solid;
      height: 10vh;
      border-radius: 40px;
      left: 35%;
      top: 10%;
      text-transform: uppercase;
      font-size: 4vh;
      transition: .25s linear;
      padding: 2vh;
      font-size: 2.5vh;
      width: 30%;

    }

    #line,
    #lang {
      position: absolute;
      font-size: 5vh;
      top: 25%;
      text-transform: uppercase;
      color: snow;
      font-weight: 400;
      width: 100%;
    }

    #hi,
    #show,
    #ar,
    #en {
      border: 1vw snow solid;
      border-radius: 40px;
      padding: 2vh;
      font-size: 2.5vh;
      width: 20%;


    }

    #hi,
    #ar {
      position: absolute;
      right: 20%;
      transition: .25s linear;
    }

    #show,
    #en {
      position: absolute;
      right: 50%;
      transition: .25s linear;
      background: white;
      color: black;


    }

    #restart:hover {
      background: snow;
      color: black;
    }

    #lang {
      top: 50%;
    }

    #ar {
      font-size: 3vh;
      padding: 2%;
    }
  </style>
</head>

<body>

  <center>
    <div class="landscap">

      <div class="vwio">
        <div class="f"></div>
        <div class="d"></div>
        <div class="gho">
        </div>
      </div>
      <h1 class="tix">R<span>O</span>TATE THE PH<span>O</span>NE</h1>
    </div>
    <div class="conener" id="conn">
      <div id="ree">
        <button id="option">SETTING</button>
        <div class="setting">
          <div class="cr" id="cr">x</div>
          <button id="restart">restart</button>
          <div id="line"><span id="t">line win</span>
            <br />
            <span id="hi">hidden</span>

            <span id="show">show</span>
          </div>

          <div id="lang">
            <span id="llo">LANGUAGE</span>
            <br />
            <span id="ar">العربية</span>

            <span id="en">ENGLISH</span>
          </div>

        </div>


      </div>
      <div class="ll" id="ll">
        <span class="sp" id="sp"><span class="xti">X</span>&<span class="oti">O</span></span>
        <div class="xx" id="xc">
          <h3>X<br><span class="xxx" id="xxx"></span></h3>
        </div>
        <div class="oo" id="oc">
          <h3>O<br><span class="ooo" id="ooo"></span></h3>
        </div>

      </div>
      <div class="g">


      </div>

      <div class="ghf">
        <div class="tt">
          <div class="t1"></div>
          <div class="t2"></div>
          <div class="t3"></div>
          <div class="t4"></div>
          <div class="drer" id="drer"></div>
          <div class="drar" id="drar"></div>

          <div class="n1" id="n1"></div>
          <div class="n2" id="n2"></div>
          <div class="n3" id="n3"></div>
          <div class="n4" id="n4"></div>
          <div class="n5" id="n5"></div>
          <div class="n6" id="n6"></div>
          <div class="n7" id="n7"></div>
          <div class="n8" id="n8"></div>

        </div>


        <div class="h" id="w1" onclick=" y(this.id)"></div>
        <div class="h" id="w2" onclick=" y(this.id)"></div>
        <div class="h" id="w3" onclick=" y(this.id)"></div>
        <div class="h" id="w4" onclick=" y(this.id)"></div>
        <div class="h" id="w5" onclick=" y(this.id)"></div>
        <div class="h" id="w6" onclick=" y(this.id)"></div>
        <div class="h" id="w7" onclick=" y(this.id)"></div>
        <div class="h" id="w8" onclick=" y(this.id)"></div>
        <div class="h" id="w9" onclick=" y(this.id)"></div>
        <div id="w10"></div>
      </div>
    </div>
  </center>
  <div class="ncli" id="no-click"></div>
  <script>
    let tite = document.getElementById("sp");
    let ee = document.getElementById("ll");

    let tt = 'x';
    wi = [];
    let num = 0;

    let vv = 1;

    let nocli = document.getElementById("no-click")
    if (sessionStorage.gf == "x") { tt = "o"; }
    let n1 = document.getElementsByClassName('n1')[0]
    let n2 = document.getElementsByClassName('n2')[0]
    let n3 = document.getElementsByClassName('n3')[0]
    let n4 = document.getElementsByClassName('n4')[0]
    let n5 = document.getElementsByClassName('n5')[0]
    let n6 = document.getElementsByClassName('n6')[0]
    let n7 = document.getElementsByClassName('n7')[0]
    let n8 = document.getElementsByClassName('n8')[0]

    // to calc num win
    function jo(wim) {
      if (wi[wim] == "x")
      {
        nocli.style.display = 'block'
        xxx.innerHTML++;
        sessionStorage.setItem('nu', xxx.innerHTML)

      }
      else if (wi[wim] == "o") {
        nocli.style.display = 'block'
        ooo.innerHTML++;
        sessionStorage.setItem('nn', ooo.innerHTML)

      }
    }

    let xxx = document.getElementById("xxx")
    let ooo = document.getElementById("ooo")

    xxx.innerHTML = 0
    ooo.innerHTML = 0
    if (sessionStorage.nu != null) {
      xxx.innerHTML = JSON.parse(sessionStorage.nu);

    }
    if (sessionStorage.nn != null) {
      ooo.innerHTML = JSON.parse(sessionStorage.nn);
    }
    // animation first

    if (tt == 'x') {
      document.getElementById("xc").style.animation = "eef 5s linear";
    }
    else if (tt == 'o') {
      document.getElementById("oc").style.animation = "ef 5s linear";
    }
    // to end the game
    function end(s) {
      document.getElementById("drar").style.animation = "none";
      document.getElementById("drer").style.animation = "none";
      if (wi[s] == "x") {
        if (localStorage.lang == "ar") {
          tite.innerHTML = '<span class="xti">x</span>  الفائز هو'
        } else {
          tite.innerHTML = '<span class="xti">x</span> is win'
        }

      } else if (wi[s] == "o") {
        if (localStorage.lang == "ar") {
          tite.innerHTML = '<span class="oti">o</span> الفائز هو'
        } else {
          tite.innerHTML = '<span class="oti">o</span> is win'
        }

      };
      setTimeout(function() {
        for (kl = 1; kl < 10; kl++) {
          document.getElementById("w" + kl).innerHTML = "";
          document.getElementById("w" + kl).style.animation = "";
          tite.innerHTML = '<span class="xti">x</span>&<span class="oti">o</span>';
        }


        nocli.style.display = 'none';
        document.getElementById("xc").style.animation = "none";
        document.getElementById("oc").style.animation = "none";
        document.getElementById("drar").style.animation = "ereff 1s linear";
        document.getElementById("drer").style.animation = "eref 1s linear";
        if (tt == 'x') {
          document.getElementById("xc").style.animation = "eef 5s linear";
        }
        else if (tt == 'o') {
          document.getElementById("oc").style.animation = "ef 5s linear";
        }

      }, 3000)
      vv = 1
      num = 0

    }

    // colect wi1 2 3 4 5 6 7 8 9
    function win() {
      for (i = 1; i <= 10; i++) {
        wi[i] = document.getElementById('w' + i).innerHTML;
      }
      // wining
      if (wi[1] == wi[2] && wi[2] == wi[3] && wi[1] != '') {
        end(1)
        w4.style.animation = "opacit 3s linear ";
        w5.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        w7.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        w9.style.animation = "opacit 3s linear ";
        n1.style.display = 'block'
        if (wi[1] == 'x') {
          n1.style.background = ' #8891E9'
        } else {
          n1.style.background = 'red'
        }
        n1.style.animation = 'n1 2s'

        setTimeout(function() {
          n1.style.display = 'none'
        }, 3000)

        jo(1)
      }
      else if (wi[4] == wi[5] && wi[5] == wi[6] && wi[4] != '') {
        end(4)
        w1.style.animation = "opacit 3s linear ";
        w2.style.animation = "opacit 3s linear ";
        w3.style.animation = "opacit 3s linear ";
        w7.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        w9.style.animation = "opacit 3s linear ";
        jo(4)

        n2.style.display = 'block'
        n2.style.animation = 'n1 2s'
        if (wi[4] == 'x') {
          n2.style.background = ' #8891E9'
        } else {
          n2.style.background = 'red'
        }
        setTimeout(function() {
          n2.style.display = 'none'
        }, 3000)

      }
      else if (wi[7] == wi[8] && wi[8] == wi[9] && wi[7] != '') {
        end(7)
        w1.style.animation = "opacit 3s linear ";
        w2.style.animation = "opacit 3s linear ";
        w3.style.animation = "opacit 3s linear ";
        w4.style.animation = "opacit 3s linear ";
        w5.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        n3.style.display = 'block'
        if (wi[7] == 'x') {
          n3.style.background = ' #8891E9'
        } else {
          n3.style.background = 'red'
        }
        n3.style.animation = 'n1 2s'
        setTimeout(function() {
          n3.style.display = 'none'
        }, 3000)
        jo(7)

      }
      else if (wi[1] == wi[4] && wi[4] == wi[7] && wi[1] != '') {
        end(1)
        w2.style.animation = "opacit 3s linear ";
        w3.style.animation = "opacit 3s linear ";
        w5.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        w9.style.animation = "opacit 3s linear ";
        jo(1)
        n6.style.display = 'block'
        n6.style.animation = 'n2 2s'
        if (wi[1] == 'x') {
          n6.style.background = ' #8891E9'
        } else {
          n6.style.background = 'red'
        }
        setTimeout(function() {
          n6.style.display = 'none'
        }, 3000)

      }
      else if (wi[2] == wi[5] && wi[5] == wi[8] && wi[2] != '') {
        end(2)
        w1.style.animation = "opacit 3s linear ";
        w3.style.animation = "opacit 3s linear ";
        w4.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        w7.style.animation = "opacit 3s linear ";
        w9.style.animation = "opacit 3s linear ";
        if (wi[2] == 'x') {
          n5.style.background = ' #8891E9'
        } else {
          n5.style.background = 'red'
        }
        jo(2)
        n5.style.display = 'block'
        n5.style.animation = 'n2 2s'
        setTimeout(function() {
          n5.style.display = 'none'
        }, 3000)
      }
      else if (wi[3] == wi[6] && wi[6] == wi[9] && wi[3] != '') {
        end(3)
        w1.style.animation = "opacit 3s linear ";
        w2.style.animation = "opacit 3s linear ";
        w4.style.animation = "opacit 3s linear ";
        w5.style.animation = "opacit 3s linear ";
        w7.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        jo(3)
        n4.style.display = 'block'
        if (wi[3] == 'x') {
          n4.style.background = ' #8891E9'
        } else {
          n4.style.background = 'red'
        }
        n4.style.animation = 'n2 2s'
        setTimeout(function() {
          n4.style.display = 'none'
        }, 3000)
      }
      else if (wi[1] == wi[5] && wi[5] == wi[9] && wi[1] != '') {
        end(1)
        w2.style.animation = "opacit 3s linear ";
        w3.style.animation = "opacit 3s linear ";
        w4.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        w7.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        jo(1)
        n7.style.display = 'block'
        n7.style.animation = 'n7 2s'
        if (wi[1] == 'x') {
          n7.style.background = ' #8891E9'
        } else {
          n7.style.background = 'red'
        }
        setTimeout(function() {
          n7.style.display = 'none'
        }, 3000)
      }
      else if (wi[3] == wi[5] && wi[5] == wi[7] && wi[3] != '') {
        end(3)
        w1.style.animation = "opacit 3s linear ";
        w2.style.animation = "opacit 3s linear ";
        w4.style.animation = "opacit 3s linear ";
        w6.style.animation = "opacit 3s linear ";
        w8.style.animation = "opacit 3s linear ";
        w9.style.animation = "opacit 3s linear ";
        jo(3)
        n8.style.display = 'block'
        if (wi[3] == 'x') {
          n8.style.background = ' #8891E9'
        } else {
          n8.style.background = 'red'
        }
        n8.style.animation = 'n8 2s'
        setTimeout(function() {
          n8.style.display = 'none'
        }, 3000)
      }
      // no body win
      if (vv == 10) {

        document.getElementById("drar").style.animation = "none";
        document.getElementById("drer").style.animation = "none";
        document.getElementById("xc").style.animation = "none";
        document.getElementById("oc").style.animation = "none";
        if (localStorage.lang == "ar") {
          tite.innerHTML = '<span class="oti">لا</span> أحد فاز';
        } else {
          tite.innerHTML = 'n<span class="oti">o</span> b<span class="oti">o</span>dy win';
        }
        if (sessionStorage.gf == "x") {
          tt = "o";

        } else if (sessionStorage.gf == "o") {
          tt = "x";

        }

        setTimeout(function() {
          for (kl = 1; kl < 10; kl++) {
            document.getElementById("w" + kl).innerHTML = "";
            document.getElementById("w" + kl).style.animation = "";
            tite.innerHTML = '<span class="xti">x</span>&<span class="oti">o</span>'
          }


          nocli.style.display = 'none';
          document.getElementById("drar").style.animation = "ereff 1s linear";
          document.getElementById("drer").style.animation = "eref 1s linear";

          if (tt == 'x') {
            document.getElementById("xc").style.animation = "eef 5s linear";
          }
          else if (tt == 'o') {
            document.getElementById("oc").style.animation = "ef 5s linear";
          }
        }, 3000)
        num = 0
        vv = 1
      }

    }
    // to playing
    function y(id) {
      let d = document.getElementById(id);
      if (tt == 'x' && d.innerHTML == '')
      {
        d.innerHTML = 'x';
        tt = 'o';
        d.style.color = "#8891E9"
        d.style.textShadow = " 0px 0px 10px #8891E9 ,0px 0px 15px #8891E9"
        tite.innerHTML = '<span class="oti">o</span>'
        vv = vv + 1;
        num++;
        hf("x");
      }
      else if (tt == 'o' && d.innerHTML == "") {
        d.innerHTML = "o";
        tt = "x"
        d.style.color = "red"
        d.style.textShadow = " 0px 0px 10px red , 0px 0px 15px red"
        tite.innerHTML = '<span class="xti">x</span>'
        vv = vv + 1;
        num++;
        hf("o");
      }
      win()

    }
    // the first
    function hf(f) {
      if (num == 1) {
        sessionStorage.gf = f
      }
    }
    // screen orientation
    setInterval(function() {
      if (screen.orientation.type == "portrait-primary") {
        document.getElementsByClassName("landscap")[0].style.display = "none";
        conn.style.display = "block";
      } else {
        document.getElementsByClassName("landscap")[0].style.display = "flex";
        conn.style.display = "none";
      }
    })
    var conn = document.getElementById("conn")

    var option = document.getElementById("option");
    var cr = document.getElementById("cr");
    // to clear setting
    cr.onclick = function() {
      document.getElementsByClassName("setting")[0].style.display = "none"
    }
    // to show setting
    option.onclick = function() {
      document.getElementsByClassName("setting")[0].style.display = "block"
    }
    //btn restart
    var restart = document.getElementById("restart");
    restart.onclick = function() {


      document.getElementById("drar").style.animation = "none";
      document.getElementById("drer").style.animation = "none";
      document.getElementById("xc").style.animation = "none";
      document.getElementById("oc").style.animation = "none";

      if (localStorage.lang == "ar") {
        tite.innerHTML = '<span class="oti">جا</span>ري التحميل';
      } else {
        tite.innerHTML = 'l<span class="oti">o</span>ading';
      }
      nocli.style.display = 'block';
      setTimeout(function() {
        for (kl = 1; kl < 10; kl++) {
          document.getElementById("w" + kl).innerHTML = "";
          document.getElementById("w" + kl).style.animation = "";
          tite.innerHTML = '<span class="xti">x</span>&<span class="oti">o</span>'
        }


        nocli.style.display = 'none';
        document.getElementById("drar").style.animation = "ereff 1s linear";
        document.getElementById("drer").style.animation = "eref 1s linear";
        tt = "x";
        sessionStorage.gf = "x";
        if (tt == 'x') {
          document.getElementById("xc").style.animation = "eef 5s linear";
        }
        else if (tt == 'o') {
          document.getElementById("oc").style.animation = "ef 5s linear";
        }
        xxx.innerHTML = "0";
        ooo.innerHTML = "0";
        sessionStorage.setItem("nu", 0);
        sessionStorage.setItem("nn", 0)
      }, 3000)

      vv = 1
      num = 0
      document.getElementsByClassName("setting")[0].style.display = "none"
    }
    // btn hidden line
    let hid = document.getElementById("hi");
    hid.onclick = function() {
      this.style.background = "snow";
      this.style.color = "black";
      document.getElementById("show").style.background = "none";
      document.getElementById("show").style.color = "snow";
      for (kl = 1; kl < 9; kl++) {
        document.getElementById("n" + kl).setAttribute("class", "nn" + kl)

      }
      localStorage.mode = "hidden"

    }
    //btn show line
    let show = document.getElementById("show")
    show.onclick = function() {
      this.style.background = "snow";
      this.style.color = "black";
      document.getElementById("hi").style.background = "none";
      document.getElementById("hi").style.color = "snow";

      for (kl = 1; kl < 9; kl++) {
        document.getElementById("n" + kl).setAttribute("class", "n" + kl)

      }
      localStorage.mode = "show"

    }
    // localStorage hidden
    if (localStorage.mode == "hidden") {
      hid.style.background = "snow";
      hid.style.color = "black";
      document.getElementById("show").style.background = "none";
      document.getElementById("show").style.color = "snow";
      for (kl = 1; kl < 9; kl++) {
        document.getElementById("n" + kl).setAttribute("class", "nn" + kl)

      }
    }

    // localStorage show
    else if (localStorage.mode == "show") {
      show.style.background = "snow";
      show.style.color = "black";
      document.getElementById("hi").style.background = "none";
      document.getElementById("hi").style.color = "snow";

      for (kl = 1; kl < 9; kl++) {
        document.getElementById("n" + kl).setAttribute("class", "n" + kl)

      }
    }
    //LANGUAGE arbic
    let ar = document.getElementById("ar");
    ar.onclick = function() {
      localStorage.lang = "ar"
      document.getElementById("option").innerHTML = "الإعدادات";
      restart.innerHTML = "إعادة البدأ";
      document.getElementById("t").innerHTML = "خطوط الفوز";
      document.getElementById("show").innerHTML = "إظهار"
      hid.innerHTML = "إخفاء"
      document.getElementById("llo").innerHTML = "اللغة";
      this.style.background = "snow"
      this.style.color = "black"
      document.getElementById("en").style.background = "none"
      document.getElementById("en").style.color = "snow"
    }
    // LANGUAGE ENGLISH
    let en = document.getElementById("en");
    en.onclick = function() {
      localStorage.lang = "en"
      document.getElementById("option").innerHTML = "SETTING";
      restart.innerHTML = "RESTART";
      document.getElementById("t").innerHTML = "LINE WIN";
      document.getElementById("show").innerHTML = "SHOW"
      hid.innerHTML = "HIDDEN"
      document.getElementById("llo").innerHTML = "LANGUAGE";
      this.style.background = "snow"
      this.style.color = "black"
      document.getElementById("ar").style.background = "none"
      document.getElementById("ar").style.color = "snow"
    }
    // loclStorge LANGUAGE arbic
    if (localStorage.lang == "ar") {
      localStorage.lang = "ar"
      document.getElementById("option").innerHTML = "الإعدادات";
      restart.innerHTML = "إعادة البدأ";
      document.getElementById("t").innerHTML = "خطوط الفوز";
      document.getElementById("show").innerHTML = "إظهار"
      hid.innerHTML = "إخفاء"
      document.getElementById("llo").innerHTML = "اللغة";
      document.getElementById("ar").style.background = "snow"
      document.getElementById("ar").style.color = "black"
      document.getElementById("en").style.background = "none"
      document.getElementById("en").style.color = "snow"
    }
    // loclStorge LANGUAGE ENGLISH
    else if (localStorage.lang == "en") {
      localStorage.lang = "en"
      document.getElementById("option").innerHTML = "SETTING";
      restart.innerHTML = "RESTART";
      document.getElementById("t").innerHTML = "LINE WIN";
      document.getElementById("show").innerHTML = "SHOW"
      hid.innerHTML = "HIDDEN"
      document.getElementById("llo").innerHTML = "LANGUAGE";
      document.getElementById("en").style.background = "snow"
      document.getElementById("en").style.color = "black"
      document.getElementById("ar").style.background = "none"
      document.getElementById("ar").style.color = "snow"
    }
  </script>
</body>

</html>
