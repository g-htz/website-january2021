<template>
  <div class="hello">
    <div class="header">
      <div class="menu">
        <div class="selection">
          <a href="https://georgehetrelezisvue.netlify.app" rel="noopener">Home</a>
        </div>
        <div class="selection">
          <a href="https://studentutsedu-my.sharepoint.com/:w:/g/personal/14123032_student_uts_edu_au/EaVCe-fgqhhBhLxHkPXR_fEBFw2fuEeEWaQp6VjxoMc8oA?e=O47IDE" target="_blank" rel="noopener">Resume</a>
        </div>
        <div class = "topName">
          George Hetrelezis
        </div>
        <div class="selection">
          About
        </div>
        <div class="selection">
          Projects
        </div>
      </div>
      <div class="george">
        <div class="letters">
          <img src="../assets/g1.png" class="letter-image">
        </div>
        <div class="letters">
          <img src="../assets/e1.png" class="letter-image">
        </div>
        <div class="letters">
          <img src="../assets/o.png" class="letter-image">
        </div>
        <div class="letters">
          <img src="../assets/r.png" class="letter-image">
        </div>
        <div class="letters">
          <img src="../assets/g2.png" class="letter-image">
        </div>
        <div class="letters">
          <img src="../assets/e2.png" class="letter-image">
        </div>
      </div>
      <div class="interlude">
          <div class="arrow">
           <a href="#linktodiv1"></a><img src="../assets/down.png" class="arrow">
          </div>
          <div class="arrow" id="linktodiv1">
            <img src="../assets/up.png" class="arrow" >
          </div>
        </div>
      <div class="myAbout">
        <div class="title">
          About Me
        </div>
        <div class="titleBody">
          <div class="aboutPicture">
            <img src="../assets/cafe.png" class="aboutPicture">
          </div>
          <div class="bio">
            Good morning <br>
            <br>
            I'm George and I'm an Enterprise Systems Development <br>
            major who's currently completing his Bachelor of Science <br>
            in Information Technology. I personally love programming and<br> 
            challenging myself by learning new web application frameworks, to which I follow it up by creating web applications from scratch. <br>
            <br>
          </div>
        </div>
      </div>
      <div class="interlude2">
          <div class="arrow">
           <a href="#linktodiv1"></a><img src="../assets/down.png" class="arrow">
          </div>
          <div class="arrow" id="linktodiv1">
            <img src="../assets/up.png" class="arrow" >
          </div>
      </div>
      <div class="title">
          Projects
        </div>
      <div class="projects">
        <div class="projectBody">
          <div class="projectBody>
            <div class="project-picture-1">
              <img src="../assets/robots.png" class="project-picture-1">
            </div>
            <div class="project-bio">
              Robots with React<br>
              <br>
              I completed this application in August 2020, and it has taught me quite <br>
              a bit about using React to create quality websitesI definitely recommend using <br>
              React for your business needs or personal portfolio due to its extensive nature <br>
              and easy to implement components.<br>
            </div>
          </div>
          <div class="project-2>
            <div class="aboutPicture">
              <img src="../assets/sage.png" class="project-picture-2">
            </div>
            <div class="project-bio">
              Adobe XD (Sage)<br>
              <br>
              My peers and I are currently creating the user interface <br> 
              for a smartphone application for an Interaction Design based <br> 
              assessment on Adobe XD. The application allows you to find the <br>
              latest technology for your business's needs, and chat with an expert <br>
               who can direct you and improve your current recommendations based on <br>
               your situation.
              <br>
            </div>
          </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: inherit;
  text-decoration: none;
}
.aboutPicture {
  align-items: center;
  display: flex;
  padding-left: 20px;
  padding-top: 15px;
  width: 64%;
}
.arrow {
  padding-top: 7px;
  margin-left: 318px;
  width: 20%;
}
.bio {
  color: #ffffff;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 25px;
  padding-right: 60px;
}
.george {
  align-items: center;
  display: flex;
  padding-top: 80px;
  padding-bottom: 40px;
  vertical-align: middle;
}
.h3 {
  margin: 40px 0 0;
}
.interlude {
  background-color: #000000;
}
.interlude2 {
  background-color: #000000;
  padding-top: 90px;
}
.ul {
  list-style-type: none;
  padding: 0;
}
.li {
  display: inline-block;
  margin: 0 10px;
}
.letter-image {
  width: 90%;
}
.menu {
  color: #ffffff;
  display: flex;
  padding-left: 100px;
  padding-top: 20px;
  text-align: justify;
}
.myAbout {
  
}
.projectBody {
  align-items: center;
  background-color: #000000;
  display: flex;
}
.projects {
  display: flex;
}
.project-bio {
  color: #ffffff;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 25px;
  margin-right: 35px;
  margin-left: 8px;
}
.project-picture-1 {
  display: flex;
  width: 80%;
}
.project-picture-2 {
  align-items: center;
  display: flex;
  padding-left: 20px;
  padding-top: 15px;
  width: 32%;
}
.selection {
  align-items: center;
  border-bottom: 2px solid #ffffff;
  color: #ffffff;
  display: flex;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  margin-right: 155px;
  
}
.topName {
  color: #ffffff;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 40px;
  margin-right: 80px;
}
.title {
  background-color: #000000;
  color: #ffffff;
  display: flex;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 50px;
  padding-left: 50px;
  text-align: left;
}
.titleBody {
  align-items: center;
  display: flex;
  vertical-align: middle;
}
</style>
