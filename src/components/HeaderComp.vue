<template>

  <div id="global" class="h-100-vh">

    <div class="container-default d_flex justify_between p_t_20">

        <div class="d_flex align_center">
          <img id="logo" src="../assets/img/work-element/dark-logo.png" alt="logo MaxCoach" class="">
        </div>

        <ul class="listTypeNone d_flex flex_row align_center">
            <li class="d_flex text_capital flex_row p-x-10 dropdown">
                <a class="text_decoration p-x-5 align_self_center" href="#">home</a>
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">pages</a>  
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">courses</a>  
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">features</a>  
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">blog</a>  
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">shop</a>  
                <i class="fa-solid fa-chevron-down"></i>
                <div class="dropdown-content">
                    <a href="#">link</a>
                    <a href="#">link</a>
                    <a href="#">link</a>
                </div>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center">
                <i id="cart" class="fa-solid fa-cart-shopping"></i>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center">  
                <i id="user" class="fa-solid fa-user"></i>
            </li>
            <li id="search" class="d_flex text_capital flex_row p-x-10 align_center b_rounded_1">
                <input type="text" placeholder="Search..." class="b_none">
                <i id="glass" class="fa-solid fa-magnifying-glass"></i>
            </li>
        </ul>

    </div>

    <div id="jumbo" class="container-default d_flex justify_between p_t_50">
        <div class="hero">
            <div>
                <div class="w_50">
                    <h2 class="text_capital fs_6">complete your dreams un javaS programming</h2>
                </div>
                <p class="fs_2 w_75">
                    Learn any coding program in distance and for a reasonable fee. You don't have to struggle alone,
                    you've got our assistance and help.
                </p>
                <button id="e-book" 
                        class="b_none b_rounded_1 text_white fs_1"><i id="e-book-icon" class="fa-solid fa-download p_e_10"></i> 
                        Download free E-book
                </button>
            </div>
        </div>

        <div id="hero">
            <img src="../assets/img/work-element/home-5-hero-image.png" alt="jumbotron">
        </div>
        

    </div>
      
  </div>

</template>

<script>


export default {
  name: 'HeaderComp',
  components: {
    
  }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/general.scss';

    #global {
        background-image: url('../assets/img/general/jumbotron.png');
        background-size: cover;
    }

    a {
        font-weight: bold
    }

    a,
    i {
        color: $blue-logo;
    }

    i {
        font-size: 0.6em;
        cursor: pointer;
    }

    #logo {
        width: 170px;
        height: 30px;
    }

    #search {
        background: $white;
        padding: 15px;
    }

    #cart {
        font-size: 1em;
    }

    #user {
        font-size: 1em;
    }

    #glass {
        font-size: 1em;
        color: $jungle-green;
    }

    #e-book {
        background: $jungle-green;
        @include paddingButton;
        cursor: pointer;
    }

    #e-book-icon {
        font-size: 1em;
        color: $white;
    }

    .hero {
        height: 100px;
        width: 500px;
    }
 

</style>
