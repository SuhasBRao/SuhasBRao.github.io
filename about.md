<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<style>
  .btn {
    background-color: DodgerBlue;
    border: none;
    color: white;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
  }
  /* Darker background on mouse-over */
  .btn:hover {
    background-color: RoyalBlue;
  }
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
    background-color: #ddd;
    color: white;
  }
  .back-to-top.show {
    opacity: 1;
  }
</style>

<a href="https://suhasbrao.github.io/" >
  <button class="btn"><i class="material-icons">home</i>
  </button>
 </a>

<a href="https://suhasbrao.github.io/about.html" id="back-to-top" class="back-to-top" style="display: inline;">Top</a>

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
---

<!--<h1 align="center"> 👋 </h1>-->

<h1 align="center"> 👨‍💻 Whoami </h1>

<p align = "center"> 
<img src = "https://images.weserv.nl/?url=https://raw.githubusercontent.com/SuhasBRao/SuhasBRao.github.io/master/assets/Profile (2).jpg?&h=300&w=300&fit=cover&mask=circle&maxage=7d&l=8" />
</p>
<!--https://github.com/neutraltone/awesome-stock-resources/blob/master/img/splash.jpg?raw=true-->

<p align="center">
  <samp>I'm Suhas B, pursuing B.E in Electronics and Communications. I'm an Open Source enthusiast who also happens to be a Pencil artist. I love Programming with Python.
   I'm more of a self learner who loves learning things from Internet apart from classroom.
  </samp>
  <br><br>
  <img src="https://komarev.com/ghpvc/?username=SuhasBRao&color=green&style=flat" color=green alt="https://suhasbrao.github.io/" /> 
 
  <!--<img src="https://komarev.com/ghpvc/?username=SuhasBRao" color=green alt="https://github.com/SuhasBRao" /> -->
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

---

<h2  align="center">&#x1F4EC; Reach me on</h2>

<p align = "center">  
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

