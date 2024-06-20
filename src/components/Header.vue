<template>
    <p class="logo m-0 p-0">
        <a class="navbar-brand p-0" href="#">
          <img src="../images/logo_50.jpg" alt="">
        </a>
    </p>
    <nav class="navbar navbar-expand-lg navbar-dark  bg-darkblue">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <p class="logoForMobile m-0 p-0">
        <img src="../images/logo_50.jpg" alt="">
      </p>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ">
          <li class="nav-item">
            <a class="nav-link">TOP</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" @click="goProfilo" data-toggle="collapse" data-target="#navbarNav">会社案内</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">製品案内</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" @click="goFooter" data-toggle="collapse" data-target="#navbarNav">所在地＆連絡先</a>
          </li>
        </ul>
      </div>
    </nav>
  </template>
  
  <script>
 
  export default {
    name: 'Header',
    methods: {
      goProfilo(){
        document.getElementById("Profile").scrollIntoView({behavior:'smooth'});
      }, 
      goFooter(){
        document.getElementById("Footer").scrollIntoView({behavior:'smooth'});
      }
    },
  };
  

  </script>
  
  <style scoped>
    ul{
        display: flex;
        justify-content: space-between;
        width: 100%;
        max-width: 1000px;
        margin: 0 auto;
        text-align: center;
    }
   li{
    font-size: 1.6rem;
   }
   .bg-darkblue{
    background-color: #003690;
    color: rgba(255,255,255,0.9) ;
   }
  p{
    background-color: rgb(153, 153, 153);
  }
  .logoForMobile{
    display: none;
  }
  .navbar-toggler-icon{
    max-width: 100%;
  }
  .nav-link:hover{
    cursor: pointer;
  }
  @media screen and (max-width: 768px) {
    .logo{
      display: none;
    }
    .logoForMobile{
      display: block;
      width: 78%;
    }
    .logoForMobile img{
      max-width: 100%;
    }
    .navbar-toggler{
      width: 15%;
    }
   
  }
  </style>
  