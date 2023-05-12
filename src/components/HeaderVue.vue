<script>
import {store} from '../store';
export default{
  name: "HeaderVue",
  data(){
    return{
      store
    }
  }
}
</script>

<template>
  <header class="py-3">
    <nav class="d-flex justify-content-between align-items-center mt-3">
      <div id="nav-left">
        <img src="../assets/img/theme_eduprime_logo.png" alt="">
      </div>
      <div id="nav-right">
        <ul class="d-flex justify-content-between align-items-center mb-0">
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Courses</a>
          </li>
          <li>
            <a href="#">About Us</a>
          </li>
          <li>
            <a href="#">News</a>
          </li>
          <li>
            <a href="#">Pages</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
          <li>
            <a href="#">Purchase</a>
          </li>
          <li class="btn btn-yellow">
            <a href="#">VIEW COURSES</a>
          </li>
        </ul>
      </div>
    </nav>
    <div id="jumbo">
      <div class="container">
        <h1>Key to your success</h1>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header{
  background-color: #E56768;
  nav{
    margin: 0 auto;
    width: 95%;
    font-weight: bold;
    #nav-left{
      width: 20%;
      img{
        display: block;
        width: 100%;
      }
    }
    #nav-right{
      width: 60%;
      .btn{
        border-radius: 40px;
        padding: 10px 20px;
      }
      .btn-yellow{
        background-color: #E9D758;
      }
    }
  }
  #jumbo{
    background-image: url(../assets/img/theme_slider2_bg-1.jpg);
    height: 500px;
  }
}

</style>
