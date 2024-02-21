
<script></script>


<template>
  <header>
    <div id="container">
      <div class="left-logo">
        <img src="../src/assets/img/logo-dark.png" alt="" class="head-logo">
      </div>
      <div class="head-link">
        <ul>
          <li>HOME<i class="fa-solid fa-check"></i></li>
          <li>LANDING<i class="fa-solid fa-check"></i></li>
          <li>PAGES<i class="fa-solid fa-check"></i></li>
          <li>DOCS<i class="fa-solid fa-check"></i></li>
        </ul>
      </div>
      <div class="icon-link">
       <ul>
        <li class="icon-search"><i class="fa-solid fa-magnifying-glass"></i></li>
        <li class="right-icon"><i class="fa-brands fa-github"></i></li>
        <li class="right-icon"><i class="fa-solid fa-book-open-reader"></i></li>
        <li class="right-icon"><i class="fa-regular fa-user"></i></li>
       </ul>
      </div>
    </div>
  </header>
  <main>
    
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


</style>