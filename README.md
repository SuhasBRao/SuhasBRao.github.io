<h3 align = "center" >
  <img src = "https://i.pinimg.com/originals/d7/bd/f1/d7bdf125ad47c0a85af91b082478a28d.gif" width = 100 height = 100 /> Namaste!
</h3>
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<style>
  .btn {
    background-color: DodgerBlue;
    border: none;
    color: white;
    padding: 5px 10px;
    font-size: 16px;
    cursor: pointer;
  }
  /* Darker background on mouse-over */
  .btn:hover {
    background-color: RoyalBlue;
  }
  /* style for material-icons */
  /* ################################################################################*/
  .material-icons {
    font-family: 'Material Icons';
    font-weight: normal;
    font-style: normal;
    font-size: 24px;  
    display: inline-block;
    line-height: 1;
    text-transform: none;
    letter-spacing: normal;
    word-wrap: normal;
    white-space: nowrap;
    direction: ltr;
    -webkit-font-smoothing: antialiased;
    text-rendering: optimizeLegibility;
    /* Support for Firefox. */
    -moz-osx-font-smoothing: grayscale;
    /* Support for IE. */
    font-feature-settings: 'liga';
  }
  .material-icons.md-16 { font-size: 16px; }
  /* Below is used to for go back to top button */
  /* ################################################################################*/
  .back-to-top {
      background-color: #04AA6D;
      color: #FFFFFF;
      opacity: 0;
      transition: opacity .6s ease-in-out;
      z-index: 999;
      position: fixed;
      right: 20px;
      bottom: 20px;
      width: 50px;
      height: 50px;
      box-sizing: border-box;
      border-radius: 50%;
    }
    a.back-to-top {
      font-weight: 1000;
      letter-spacing: 2px;
      font-size: 14px;
      text-transform: uppercase;
      text-align: center;
      line-height: 1.6;
      padding-left: 2px;
      padding-top: 14px;
    }
    .back-to-top:hover, .back-to-top:focus, .back-to-top:visited {
      color: white;
    }
    .back-to-top.show {
      opacity: 1;
    }
  /* side navigation bar */
  /* loader */
  .dots-3 {
    width:50px;
    height:24px;
    background: 
      radial-gradient(circle closest-side,currentColor 90%,#0000) 0%   50%,
      radial-gradient(circle closest-side,currentColor 90%,#0000) 50%  50%,
      radial-gradient(circle closest-side,currentColor 90%,#0000) 100% 50%;
    background-size:calc(100%/3) 12px;
    background-repeat: no-repeat;
    animation:d3 1s infinite linear;
  }
  @keyframes d3 {
      20%{background-position:0%   0%, 50%  50%,100%  50%}
      40%{background-position:0% 100%, 50%   0%,100%  50%}
      60%{background-position:0%  50%, 50% 100%,100%   0%}
      80%{background-position:0%  50%, 50%  50%,100% 100%}
  }
</style>

<a href="https://suhasbrao.github.io/" id="back-to-top" class="back-to-top" style="display: inline;">Top</a>
<!--####################################################-->

<!-- Fades in the button when you scroll down -->
<script>
  var link = document.getElementById("back-to-top");
  var amountScrolled = 250;

  window.addEventListener('scroll', function(e) {
      if ( window.pageYOffset > amountScrolled ) {
          link.classList.add('show');
      } else {
          link.className = 'back-to-top';
      }
  });  
<!-- Scrolls to Top -->
  link.addEventListener('click', function(e) {
      e.preventDefault();

      var distance = 0 - window.pageYOffset;
      var increments = distance/(500/16);
      function animateScroll() {
          window.scrollBy(0, increments);
          if (window.pageYOffset <= document.body.offsetTop) {
              clearInterval(runAnimation);
          }
      };
      // Loop the animation function
      var runAnimation = setInterval(animateScroll, 16);
  });
</script>
 <!-- This function is used to create read more button -->
<script>
  function myFunction() {
    var dots = document.getElementById("dots");
    var moreText = document.getElementById("more");
    var btnText = document.getElementById("myBtn");

    if (dots.style.display === "none") {
      dots.style.display = "inline";
      btnText.innerHTML = "Read more"; 
      moreText.style.display = "none";
    } else {
      dots.style.display = "none";
      btnText.innerHTML = "Read less"; 
      moreText.style.display = "inline";
    }
  }
</script>

<p id="about">
  <h1 align="left"> 👨‍💻 Whoami </h1>

---

  <p align = "center"> 
  <img src = "https://images.weserv.nl/?url=https://raw.githubusercontent.com/SuhasBRao/SuhasBRao.github.io/master/assets/Profile (2).jpg?&h=300&w=300&fit=cover&mask=circle&maxage=7d&l=8" />
  </p>
  <!--https://github.com/neutraltone/awesome-stock-resources/blob/master/img/splash.jpg?raw=true-->

  <p align="center">
    <samp>Pursuing B.E in Electronics and Communication. Passionate about implementing and launching new projects. I'm more of a self learner who loves to learn from internet apart from classroom. <br>Ever since I started using Linux in my first year of college, I’m exploring its nuts and bolts.
    Open source Enthusiast and passionate about coding.
    I'm an artist who has also worked as a commission artist. Super positive and I always look forward for new adventures around Tech.
    </samp>
    <br><br>
    <img src="https://komarev.com/ghpvc/?username=SuhasBRao&color=green&style=flat" color=green alt="https://suhasbrao.github.io/" /> 
    <!--<img src="https://komarev.com/ghpvc/?username=SuhasBRao" color=green alt="https://github.com/SuhasBRao" /> -->
  </p>
</p>
<h2 align = "center" >
 <samp> <img src = "https://image.flaticon.com/icons/png/128/1087/1087840.png" width = 30 height = 30 />
  Technologies
 </samp>
</h2>

##### Languages

  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />
  <img alt="C" src="https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=white&style=for-the-badge" />
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?logo=c++&logoColor=white&style=for-the-badge" />

##### Libraries:

  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv5&logoColor=white&style=for-the-badge" />
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?logo=numpy3&logoColor=white&style=for-the-badge" />
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=for-the-badge" />

##### Version Control System:

<img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge" />


![github stats](https://github-readme-stats.vercel.app/api?username=SuhasBRao)
<!--![Top Languages Card](https://github-readme-stats.vercel.app/api/top-langs/?username=SuhasBRao)
-->

</section>

<p id = "Project">
<h3><samp>Project sites:</samp></h3>

---

- <h3><img src = "https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fbestanimations.com%2FAnimals%2FReptiles%2Fsnakes%2Fanimated-cobra-snake-gif-2.gif&f=1&nofb=1" width = 70 height = 70/>Snake game using Python</h3>
<p>Who has not played the historic Snake game on Nokia mobile phones. Still, to this very day, people of all ages will have heard of Snake – they might have even played the original, or know an older person who has. I myself was addicted to the game back in my childhood. Though modern games have advanced user interfaces and better graphics, I still miss that excitement while playing them. I always wanted to recreate that excitement and feeling, Thanks to the programming languages which allow us to build such cool stuffs.
<a href = "https://suhasbrao.github.io/Snake-game/">
  <button class="btn"> View more
  </button>
</a></p>

- <h3><img src ="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fgifimage.net%2Fwp-content%2Fuploads%2F2017%2F10%2Fmicrophone-gif-12.gif&f=1&nofb=1" width = 50 height = 50 />Text to Speech Converter</h3>
<p>The project aims to convert text to speech. This is achieved using gTTS engine which has very natural sounding voices. Python language has been used. Python allows us to write a neat and simple code to complete the work. Here the user needs to be connected to the internet while running the .py file. 
<a href = "https://suhasbrao.github.io/Text-To-Speech/" >
  <button class="btn"> View more
  </button>
</a></p>

- <h3><img src="https://media0.giphy.com/media/rxFW7n1NU7E6bwJ5ht/giphy.gif?cid=ecf05e4744p6phdsmu8nr73m9k0rixokm92401r15rsz1r62&rid=giphy.gif&ct=g" width = 65 height = 65 />Face Detection</h3>
<p>Face detection is the first and foremost step for face recognition. It is used to detect faces in images. Face detection is a part of object detection and can be used in many areas such as security, bio-metrics, law-enforcement, entertainment, personal safety etc.
Face detection is an AI-based computer technology that can identify and locate the presence of human faces in digital photos and videos. Due to the advancements in face detection technology, It is now possible to detect faces in an image or video, regardless of head pose, lighting conditions, and skin tone
<a href = 'https://suhasbrao.github.io/FaceDetection/' >
  <button class="btn"> View more
  </button>
</a></p>

#### More projects 
<section align = "center">
<div class="dots-3"></div>
</section>

<h2  align="center">&#x1F4EC; Reach me on</h2>

---

<p id = "reach_me_on" align = "center" >  
  <a href="https://www.instagram.com/suhasbrao/">
    <img
      alt="Instagram"
      src = "https://image.flaticon.com/icons/png/128/185/185985.png"
      width = 35
      height = 35
    />
  </a>
  &emsp;
  <a href="mailto:raos04567@gmail.com?subject=Hello%20Suhas B,%20From%20Github">
    <img 
      src = "https://image.flaticon.com/icons/png/128/552/552486.png"
      width = 35
      height = 35   
    />
  </a>
  &emsp;
  <a href="https://in.linkedin.com/in/suhasbrao?trk=profile-badge">
    <img 
      src = "https://image.flaticon.com/icons/png/128/185/185964.png"
      width = 35
      height = 35   
    />
  </a>
  &emsp;
  <a href="https://www.quora.com/profile/Suhas-Rao-66">
    <img 
      src = "https://image.flaticon.com/icons/png/128/185/185976.png"
      width = 35
      height = 35   
    />
  </a>
&nbsp;&nbsp;&nbsp;&nbsp;
</p>

