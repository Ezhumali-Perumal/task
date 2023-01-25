<!-- Please remove this file from your project -->
<template>
  <section>
    <div class="">
      <header>
        <nav id="navbar1" class="header-navbar">
          <div id="header-banner"></div>
          <ul>
            <ol>
              <a href="#">How it works</a>
            </ol>
            <ol>
              <a href="#">FAQ</a>
            </ol>
            <ol>
              <a href="#">Pricing</a>
            </ol>
          </ul>
          <ul></ul>
          <ul>
            <ol>
              <button class="log-btn" id="login-btn">Login</button>
            </ol>
            <ol>
              <button class="log-btn" id="signup-btn">Sign Up</button>
            </ol>
          </ul>
        </nav>
        <div id="header-banner">
          <div class="header-titel">
            <h1>
              Smart Watch App <br />
              Landing Page
            </h1>
          </div>
          <div class="header-image">
            <img src="../static/images/Smartwatch.png" />
          </div>
        </div>
      </header>
      <dev class="">
        <div class="card">
          <img src="./static/images/1.png"/>
          <img class="card-img" src="../static/images/download.png" />
          <h2 class="card-titel">
            <spen style="color: #2186eb">Download</spen> Our App
          </h2>
          <p class="card-pera">
            Help in theory, our a the and fixed housed commas, having of a the
            that deceleration they or have of there
          </p>
        </div>
      </dev>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style>
@import url("//fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&amp;lang=en");

#header-banner {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url("./static/images/background.png");
  background-size: cover;
  background-position: center;
  z-index: -1;
  min-height: 1200px;
}

#header-banner:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url("./static/images/background.png");
  background-size: cover;
  background-position: center;
  z-index: -1;
}
#header-banner {
  background-image: url("./static/images/background.png");
  background-size: cover;
  background-position: center;
}
.header-navbar {
  display: flex !important;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
  align-items: center;
}
ul {
  margin-top: 0;
  margin-bottom: 1rem;
  display: flex;
  padding: 20px 96px;
  font-family: bold;
}
ul,
oi {
  padding-right: 148px;
  font-size: 16px;
  font-family: bold;
}
a {
  color: #ffffff;
  text-decoration: none;
  background-color: transparent;
  font-family: bold;
}
.log-btn {
  width: 100px;
  border: none;
  background: none;
  color: azure;
  font-size: 16px;
  font-family: bold;
}
.log-btn:hover {
  border: solid;
  border-radius: 19px;
  text-align: center;
}
.header-titel {
  text-align: center;
  margin-top: 186px;
  color: white;
  font-size: 66px;
}
.header-image {
  margin-left: 716px;
  margin-top: 61px;
  margin-bottom: 55px;
}
.card {
  position: absolute;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 1px solid rgba(0, 0, 0, 0.125);
  border-radius: 0.25rem;
  margin-top: 73pc;
  width: 379px;
  height: 319px;
  margin-left: 172px;
  background-repeat: no-repeat;
}
.card-img {
  width: 48px;
  height: 63px;
  margin-left: 26px;
  margin-top: 63px;
}
.card-titel {
  margin: 20px 20px;
}
.card-pera {
  margin: 20px 20px;
}
</style>
