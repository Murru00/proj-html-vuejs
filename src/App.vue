
<script></script>


<template>
  <header>
    <div id="container">
      <div class="left-logo">
        <img src="../src/assets/img/logo-dark.png" alt="" class="head-logo">
      </div>
      <div class="head-link">
        <ul>
          <li>HOME</li>
          <li>LANDING<i class="fa-solid fa-check"></i></li>
          <li>PAGES<i class="fa-solid fa-check"></i></li>
          <li>DOCS<i class="fa-solid fa-check"></i></li>
        </ul>
      </div>
      <div class="icon-link">
       <ul>
        <li class="icon-search"><i class="fa-solid fa-magnifying-glass"></i></li>
        <li class="right-icon"><i class="fa-brands fa-github"></i></li>
        <li class="right-icon"><i class="fa-brands fa-stack-overflow"></i></li>
        <li class="right-icon"><i class="fa-regular fa-user"></i></li>
       </ul>
      </div>
    </div>
  </header>
  <main>
    <div id="development">
      <div class="col-5">
        <div class="dev-target">Development</div>
        <div><h2> A complete Developer Toolset</h2></div>
        <p>Launch your campaign and benefit from our expertise on designing and managing conversion centered bootstrao4 html page.</p>

        <div class="btn-devolpment">
          <button type="button" class="btn btn-primary">Get Started</button>
          <button type="button" class="btn btn-outline-primary">Documentation</button>
        </div>
        <p>Current Version v2.6.0</p>
      </div>
      <div class="col-3">
        <img src="../src/assets/img/about.png" alt="">
      </div>
    </div>

    <div id="container" class="company-img">
      <img src="./assets/img/amazon.svg" class="comp-img-logo" alt="">
      <img src="./assets/img/google.svg" class="comp-img-logo" alt="">
      <img src="./assets/img/lenovo.svg" class="comp-img-logo" alt="">
      <img src="./assets/img/paypal.svg" class="comp-img-logo" alt="">
      <img src="./assets/img/shopify.svg" class="comp-img-logo" alt="">
      <img src="./assets/img/spotify.svg" class="comp-img-logo" alt="">
    </div>
    

    <div class="container">
      <h3>Key Features</h3>
      <p>Start working with Landrick that can provide everything you need to generate <br> awaraness, drive traffic, connect.</p>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-3">
          <i class="fa-solid fa-layer-group icon-row"></i>
          <h4>Modular</h4>
        </div>
        <div class="col-3">
          <i class="fa-brands fa-chromecast icon-row"></i>
          <h4>responsive</h4>
        </div>
        <div class="col-3">
          <i class="fa-solid fa-expand icon-row"></i>
          <h4>Customizable</h4>
        </div>
        <div class="col-3">
          <i class="fa-solid fa-maximize icon-row"></i>
          <h4>Scalable</h4>
        </div>
      </div>
    </div>
  </main>
  <footer></footer>
</template>



<style>



.head-logo{
  width: 170px;
}

.left-logo{
  margin-top: 35px;
}

.row{
  display: flex;
  padding: 35px;
  text-align: center;
}

.icon-row{
  font-size: 30px;
  background-color: #c6c6c6;
  width: 50px;
  height: 40px;
  
  text-align: center;
  margin-top: 50px;
  border-radius: 7px;
}

ul{
  display: flex;
  gap: 30px;
  list-style-type: none;
  margin-top: 40px;
  cursor: pointer;
}

#container{
  display: flex;
  justify-content: space-around;
}

.right-icon{
  background-color: rgb(180, 177, 177);
  color: rgb(60, 3, 251);
  border: 2px solid rgb(180, 177, 177);
  border-radius: 3px;
  font-size:20px;
  
}

.icon-search{
  color: grey;
 
  
}
  
#development{
  display: flex;
  margin-top: 50px;
  margin-left: 150px;
}
.col-5{
  width: 50%;
  height: 300px;
}
.col-3{
  width: 30%;
  height: 300px;
  border: 2px solid black;
}

.dev-target{
  color: blue;
  background-color: #c6c6c6;
  font-size: 15px;
  border: 1px solid gray;
  width: 85px;
  border-radius: 4px;
}
p{
  color: grey;
  font-size: 17px;
  font-weight: bold;
}

h2{
  font-size: 55px;
}


.comp-img-logo{
  width: 90px;
}

.company-img{
  margin-top: 250px;
  background-color: #f8f9fc;
}

.container{
  margin-left: 60px;
}

h3{
  font-size: 35px;
}
h4{
  font-size: 20px;
}
</style>