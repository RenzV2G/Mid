<template>
<body>
  <div id="header"></div>
<div class="left"></div>
<div class="stuff">
  <br><br>
  <h1>Resume</h1>
  <h2>Renz Andrew D. Vitug</h2>
  <hr />
  <br>
  <br>
  <h1>Profile</h1>
  <br>

  <div>
    <h3>Objective</h3>
    <li>trained in conflict resolution</li>
    <li>Highly motivated to do the task</li>
  </div>
<br>
<br>
  <h3>Name: Renz Andrew Dimarucut Vitug</h3>
  <h4>Course: Information Technology (Web Development)</h4>
<br>
<br>

<div>
  <h3>Education</h3>
  <li>Elementary: Cabetican Elementary School</li>
  <li>Junior high and Senior High: Holy Angel University</li>
  <li>College: Holy Angel University (undergraduate)</li>
</div>
<br>
<br>
<div>
  <h3>Programming Languages</h3>
  <li>PHPl</li>
  <li>Wordpress</li>
  <li>Java</li>
  <li>Python</li>
  <li>Linux</li>
</div>
<br>
<br>
<div>
  <h3>Skills</h3>
  <li>Editting</li>
  <li>Web design</li>
  <li>UI/UX design</li>
  <li>Logo making</li>
  <li>HTML Website Development</li>
</div>
<br>
<br>
<div>
  <h3>Training/Seminars</h3>
  <li>Redhat</li>
  <li>W3schools</li>
  <li>cisco</li>
</div>
<br>
<br>
<div>
  <h3>Technologies</h3>
  <li>Tablet</li>
  <li>Mobile phones</li>
  <li>Computer</li>
</div>
<br>
<br>
  

</div>
<div class="right"></div>
<div id="footer">
  <h2 id="name">Vitug</h2></div>
</body>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'My Resume'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  max-width: 700px;
  margin: auto;
}


/*body {
    min-width: 500px;
}*/

div {
  border-radius: 5px;
}

#header {
  height: 40px;
  width: 100%;
  background-color: #ffcccc;
  position: fixed;
  z-index: 1;
}

#title {
  margin-left: 3%;
}

#footer {
  height: 50px;
  width: 100%;
  background-color: #ffcccc;
  clear: both;
  position: relative;
}

.left {
  height: 1000px;
  width: 45px;
  background-color: #e0eeee;
  float: left;
  position: fixed;
}

.right {
  height: 1000px;
  width: 45px;
  background-color: #e0eeee;
  float: right;
  position: inherit;
}

.stuff {
  display: inline-block;
  margin-top: 6px;
  margin-left: 55px;
  width: 75%;
  height: 1000px;
}

p,
li {
  font-family: 'Cormorant Garamond';
}

.head {
  font-size: 20px;
}

#name {
  font-family: Sacramento;
  float: right;
  margin-top: 10px;
  margin-right: 4%;
}

a {
  color: black;
  text-decoration: none;
}

@media only screen and (max-width: 430px) {
  .left,
  .right {
    display: none;
  }
  .stuff {
    width: 100%;
    margin-left: 10px;
  }
}
</style>
