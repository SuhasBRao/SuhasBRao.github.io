<h3 align = "center" >
  <img src = "https://cdn.iconscout.com/icon/premium/png-128-thumb/namaste-3754435-3136262.png" width = 70 height = 70 /> Namaste!
</h3>

<link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">
<link href="/assets/style.css" rel="stylesheet">

<a href="https://suhasbrao.github.io/" id="back-to-top" class="back-to-top" style="display: inline;"><i class="ri-arrow-up-line"></i></a>

<script>
  var link = document.getElementById("back-to-top");
  var amountScrolled = 300;

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

<p id="about">
  <h1 align="left">
    <samp>
      <img src = "https://image.flaticon.com/icons/png/128/1177/1177568.png" width = 50 height = 50 /> Whoami
    </samp>
  </h1>
  <hr class="hr1" />
<!-- below is used to display image -->
  <p align = "center">
  <img src = "https://images.weserv.nl/?url=avatars.githubusercontent.com/u/65769327?v=4&h=300&w=300&fit=cover&mask=circle&maxage=7d" />
  </p>
<!-- About me -->
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

<!-- Tools and Technology section -->
<h1 align = "left" >
 <samp>
  <img src = "https://image.flaticon.com/icons/png/128/1087/1087840.png" width = 50 height = 50 />
  Technologies
 </samp>
</h1>
<hr class="hr1" />
<h4>Languages:</h4>

  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />
  <img alt="C" src="https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=white&style=for-the-badge" />
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?logo=c++&logoColor=white&style=for-the-badge" />

<h4>Libraries:</h4>

  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv5&logoColor=white&style=for-the-badge" />
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?logo=numpy3&logoColor=white&style=for-the-badge" />
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=for-the-badge" />

<h4>Version Control System:</h4>

<img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge" />

![github stats](https://github-readme-stats.vercel.app/api?username=SuhasBRao)



<!-- Project setion --->
<p id = "Project">
<h1>
  <samp>
  <img src = "https://image.flaticon.com/icons/png/128/4005/4005054.png" width = 50 height = 50 />
  Projects
  </samp>
</h1>
<hr class="hr1" />
<h3>
  <img src = "https://image.flaticon.com/icons/png/128/3662/3662068.png" width = 50 height = 50/>
  Snake game using Python:
</h3>
<p style="font-family:perpetua;font-size:130%;">Who has not played the historic Snake game on Nokia mobile phones. Still, to this very day, people of all ages will have heard of Snake – they might have even played the original, or know an older person who has. I myself was addicted to the game back in my childhood. Though modern games have advanced user interfaces and better graphics, I still miss that excitement while playing them. I always wanted to recreate that excitement and feeling, Thanks to the programming languages which allow us to build such cool stuffs.
<a href = "https://suhasbrao.github.io/Snake-game/">
  <button class="btn"> View more
  </button>
</a></p>

<h3>
  <img src ="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fgifimage.net%2Fwp-content%2Fuploads%2F2017%2F10%2Fmicrophone-gif-12.gif&f=1&nofb=1" width = 50 height = 50 />
  Text to Speech Converter:
</h3>
<p style="font-family:perpetua;font-size:130%;">The project aims to convert text to speech. This is achieved using gTTS engine which has very natural sounding voices. Python language has been used. Python allows us to write a neat and simple code to complete the work. Here the user needs to be connected to the internet while running the .py file.
<a href = "https://suhasbrao.github.io/Text-To-Speech/" >
  <button class="btn"> View more
  </button>
</a>
</p>

<h3>
  <img src="https://image.flaticon.com/icons/png/128/2199/2199469.png" width = 65 height = 65 />
  Face Detection:
</h3>
<p style="font-family:perpetua;font-size:130%;">Face detection is the first and foremost step for face recognition. It is used to detect faces in images. Face detection is a part of object detection and can be used in many areas such as security, bio-metrics, law-enforcement, entertainment, personal safety etc.
Face detection is an AI-based computer technology that can identify and locate the presence of human faces in digital photos and videos. Due to the advancements in face detection technology, It is now possible to detect faces in an image or video, regardless of head pose, lighting conditions, and skin tone
<a href = 'https://suhasbrao.github.io/FaceDetection/' >
  <button class="btn"> View more
  </button>
</a></p>

<h3> More projects </h3>
<div class="dots-3"></div>

&nbsp;&nbsp;&nbsp;&nbsp;

<!-- Reach me on section -->
<h1  align="left">&#x1F4EC; Reach me on</h1>
<hr class="hr1" />
&nbsp;&nbsp;&nbsp;&nbsp;
<p id = "reach_me_on" align = "center" >
  <a href="https://www.instagram.com/suhasbrao/">
    <img
      alt="Instagram"
      src = "https://image.flaticon.com/icons/png/128/185/185985.png"
      width = 50
      height = 50
    />
  </a>
  &emsp;
  <a href="mailto:raos04567@gmail.com?subject=Hello%20Suhas B,%20From%20Github">
    <img
      src = "https://image.flaticon.com/icons/png/128/552/552486.png"
      width = 50
      height = 50   
    />
  </a>
  &emsp;
  <a href="https://in.linkedin.com/in/suhasbrao?trk=profile-badge">
    <img
      src = "https://image.flaticon.com/icons/png/128/185/185964.png"
      width = 50
      height = 50   
    />
  </a>
  &emsp;
  <a href="https://www.quora.com/profile/Suhas-Rao-66">
    <img
      src = "https://image.flaticon.com/icons/png/128/185/185976.png"
      width = 50
      height = 50   
    />
  </a>
&nbsp;&nbsp;&nbsp;&nbsp;
</p>
