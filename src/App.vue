<template>
 <div id="app">
   <body>
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </body>
  <!--  <amplify-authenticator> 
      <amplify-sign-in header-text="Sign In" slot="sign-in"></amplify-sign-in> -->
      <div>
        <my-header></my-header>
        <my-summary></my-summary>
        <my-experience></my-experience>
        <my-projects></my-projects>
        <my-education></my-education>
        <my-skills></my-skills>
      <!--  <div id="amplify-signout">
          <amplify-sign-out></amplify-sign-out>
        </div> -->
      </div>
  <!--  </amplify-authenticator> -->
  </div> 
</template>

<script>
import Header from './components/Header';
import Summary from './components/Summary';
import Experience from './components/Experience';
import Projects from './components/Projects';
import Education from './components/Education';
import Skills from './components/Skills';


export default {
  name: "App",
  components: {
    'my-header':Header, 'my-summary':Summary,
    'my-experience':Experience, 'my-projects':Projects,
    'my-education':Education, 'my-skills':Skills
  }
};
</script>

<!-- change 2nd body back to #app when authentication is turned on -->
<style>
body {
  margin: 0
}
body {
  font-family:  "Baskerville", "Baskerville Old Face";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}
.signout {
  background-color: #ededed;
  margin: 0;
  padding: 11px 0px 1px;
}
</style>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  color: white;
}
img{
    border-radius: 50%;
}
</style>