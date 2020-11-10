
<style>
body {
  background-image:url("~@/assets/leaf.jpg");
  background-size: auto auto;
  background-repeat: no-repeat;
  background-position: center; /* Center the image */
  padding-bottom: 0;
}
</style>

<template>
  <body>
    <head>
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <div class="topnav">
    <a href="#app">Home</a>    
    <a href="#summary">Summary</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#projects">Volunteer Work</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>    
    
    </div>

    <table style="width:90%; margin-left: auto; margin-right: auto; font-size:4vw;">
      <tr>
        <td>
          <img src="~@/assets/pic.png" alt="Profile Picture" class="responsive">
        </td>
      </tr>
      <tr>
        <td style="font-size: 35px">
          NICOLEE BROWN
        </td>
      </tr>
      <tr>
        <td style="font-size: 25px"> 
          SOFTWARE ENGINEER
        </td>
      </tr>
    </table>

    <table style="width:7%; margin-left: auto; margin-right: auto; font-size:3vw;">
      <tr>
        <td>
          <a href="https://www.linkedin.com/in/nicolee-brown/" target="_blank"><img src="~@/assets/linkedin.png" title="Linkedin" alt="Linkedin Link"></a>
        </td>
        <td>
          <a href="mailto:nicoleeb22@gmail.com" target="_blank"><img src="~@/assets/mail.png" style="width:29px;height:29px;"></a>
        </td> 
      </tr>
    </table>
  </body>
</template>

<script>
   export default{

   }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p{
    color: #000000;
    font-size: 50px;
    margin-left: 100;
    margin: 0;
}

.responsive {
  width: 100%;
  max-width: 250px;
  height: auto;
}
img {
    border-radius: 50%;
    padding: 5px;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  display: inline-block;  
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}

</style>