# Doreen Wiggins
I am a Jr. Developer who is passionate about writing clean, reusable code that improves the user experience!

## About Me
I completed the Full Stack Developer Bootcamp at UNH, and have a BA in Mathematics.  
In my years spent as a Bank Manager, I have become an expert at problem solving and thinking outside the box.  When I used the bank software I would often think of ways it could be more intuitive and user friendly.
Fast forward to my next job as a Jr. Data Engineer at Recordsforce where I was on the team to test and give feedback on the new version of their PACE software.  When PACE was sold to outside companies I was responsible for conducting the new user training.  I also developed some standard and custom reports using SQL Server/SSMS and Telerik Report Designer.

## Skills
- HTML
- CSS
- Bootstrap
- Javascript
- JQuery
- GitHub
- Node.js
- MySql
- SQL Server/SSMS
- Telerik Report Designer
- MongoDB
- Agile/Scrum
- Azure for bug tracking

## Contact
[LinkedIn](https://www.linkedin.com/in/doreen-m-wiggins)

#536594
#3e4a72
#232B3F
#61497e
#5c5376
#595e8c
#a78bb7
#938fb8





#758c86
#547689
#677c85

#295a8d
#296193

<!-- Option 1 -->
.overlay {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: linear-gradient(135deg, rgba(255, 99, 71, 0.6), rgba(65, 105, 225, 0.6));
  animation: gradientShift 8s ease infinite;
  z-index: 1;
}

@keyframes gradientShift {
  0% {
    background: linear-gradient(135deg, rgba(255, 99, 71, 0.6), rgba(65, 105, 225, 0.6));
  }
  50% {
    background: linear-gradient(135deg, rgba(65, 105, 225, 0.6), rgba(124, 252, 0, 0.6));
  }
  100% {
    background: linear-gradient(135deg, rgba(255, 99, 71, 0.6), rgba(65, 105, 225, 0.6));
  }
}

<!-- Option 2 -->
.overlay {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background-color: rgba(30, 144, 255, 0.4);
  animation: fadeOverlay 6s ease-in-out infinite alternate;
  z-index: 1;
}

@keyframes fadeOverlay {
  0% {
    background-color: rgba(30, 144, 255, 0.4);
  }
  50% {
    background-color: rgba(255, 165, 0, 0.4);
  }
  100% {
    background-color: rgba(50, 205, 50, 0.4);
  }
}

<!-- Option 3 -->
<div class="blob-container">
  <div class="blob blob1"></div>
  <div class="blob blob2"></div>
</div>


.blob-container {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  overflow: hidden;
  z-index: 1;
}

.blob1 {
  position: absolute;
  width: 300px;
  height: 300px;
  background: rgba(255, 99, 71, 0.3);
  filter: blur(100px);
  animation: moveBlob 20s infinite ease-in-out;
  border-radius: 50%;
}

.blob2 {
  background: rgba(30, 144, 255, 0.3);
  left: 50%;
  top: 30%;
  animation-delay: 5s;
}

@keyframes moveBlob {
  0% {
    transform: translate(0, 0) scale(1);
  }
  50% {
    transform: translate(50px, 100px) scale(1.2);
  }
  100% {
    transform: translate(0, 0) scale(1);
  }
}

<!-- Option 4 -->
.overlay {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: linear-gradient(270deg, rgba(255, 0, 150, 0.3), rgba(0, 204, 255, 0.3), rgba(0, 255, 153, 0.3));
  background-size: 600% 600%;
  animation: colorSweep 15s ease infinite;
  z-index: 1;
}

@keyframes colorSweep {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

<!-- layering  with text -->
<!-- <div class="background-image">
  <div class="overlay"></div>
  <div class="text">
    <h1>Hello World</h1>
    <p>Overlay magic happening behind me!</p>
  </div>
</div> -->

.background-image {
  position: relative;
  background-image: url('yourimage.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  color: white;
}

.text {
  position: relative;
  z-index: 2;
  padding: 2rem;
}

Silver (#cccccc)
#f0f0f0
#ebebeb
#e6e6e6
#e0e0e0
#cccccc

Black White (#fffff8)
#fffff8

Tower Gray (#bobec5)
#d0d8dc
#c8d2d6
#d8dfe2


Alto (#e0e0e0)
#f6f6f6
#f3f3f3
#f0f0f0
#ececec

Desert Storm (#efefee)
#f1f1f0

Bismark (#496d87)
#a4b6c3
#b6c5cf
#c8d3db
#dbe2e7



