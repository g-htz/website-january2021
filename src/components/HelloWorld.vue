<template>
  <div class="hello">
    <div class="header">
      <div class="menu">
        <div class="selection">
          Home
        </div>
        <div class="selection"><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">Resume</a>
        </div>
        <div class="topName">
          George Hetrelezis
        </div>
        <div class="selection">
          Projects
        </div>
        <div class="selection">
          About
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
      <div class="projects">
        <div class="title">
          Projects
        </div>
        <div class="projectBody">
          <div class="project-icons">
            <img src="../assets/robots.png" class="project-icons">
          </div>
          <div class="project-icons">
            <img src="../assets/sage.png" class="project-icons">
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
.aboutPicture {
  align-items: center;
  display: flex;
  padding-left: 20px;
  padding-top: 15px;
  width: 64%;
}
.arrow {
  padding-top: 7px;
  margin-left: auto;
  margin-right: auto;
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
  padding-top: 125px;
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
  flex: 1;
  align-items: center;
  border-bottom: 2px solid #ffffff;
  color: #ffffff;
  cursor: pointer;
  display: flex;
  justify-content: center;
  padding-top: 20px;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  width: 100%;
}
.myAbout {
  
}
a {
  color: inherit;
  text-decoration: none;
}
.projectBody {
  background-color: #000000;
  display: flex;
  padding-bottom: 275px;
}
.project-icons {
  padding-right: 50px;
  width: 60%;
}
.selection {
  flex: 1;
  align-items: center;
  border-bottom: 2px solid #ffffff;
  color: #ffffff;
  cursor: pointer;
  display: flex;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  justify-content: center;
  text-align: center;
  width: 10%;
  
}
.topName {
  color: #ffffff;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 40px;
}
.title {
  background-color: #000000;
  color: #ffffff;
  display: flex;
  font-family: "Segoe UI", Frutiger, "Frutiger Linotype", "Dejavu Sans", "Helvetica Neue", Arial, sans-serif;
  font-size: 50px;
  padding-left: 85px;
  text-align: left;
}
.titleBody {
  align-items: center;
  display: flex;
  vertical-align: middle;
}
</style>
