<template>
  <div id="container">
    <img id="logo"
         src="../assets/blackLogo.png">
    <h1 id="title">Kent Hack Enough</h1>
    
    <div id="titleInfo">
      <h2 id="date">October ?th - ?th</h2>
      <h2 id="location">Kent State Library</h2>
    </div>
    
    <!-- This div is for before the application is done, just to promote your site. The focus is making sure sponsors know where to go. -->
    <div id="staticSite">
      
    </div>
    
    <!-- This div is for once the application is launched-->
    <div id="applicationSite">
      <button class="mainBtn" id="apply">APPLY NOW!</button>
      <br>
      <button class="mainBtn" id="login">Login</button>
    </div>
  
  </div>
</template>

<style scoped>
  #container {
    min-height: 100vh;
  }
h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
  
  
  #container {
    text-align: center;
  }
  
  #logo {
    animation: fadein 1s linear;
    margin-top: 40px;
    margin-bottom: -60px;
    /* This margin makes the logo look more centered */
    margin-right: 25px;
  }
  
  #title {
    font-size: 35px;
  }
  
  #location {
    margin-top: -10px;
  }
  
  .mainBtn {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    padding: 20px 40px 20px 40px;
    background: white;
    font-size: 20px;
    border: solid black 2px;
    border-top-left-radius: 10% 20%;
    border-top-right-radius: 10% 20%;
    border-bottom-left-radius: 10% 20%;
    border-bottom-right-radius: 10% 20%;
    margin: 10px;
    transition-duration: .2s;
    cursor: pointer;
    outline: none;
  }
  .mainBtn:hover {
    background: black;
    color: white;
    border: solid gray 2px;
  }
  
  
  @keyframes fadein {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>

<script>


export default {
  name: 'Main',
  data() {
    return {
    };
  },
};
</script>