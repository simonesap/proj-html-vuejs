<template>

  <div id="global" class="h-40-vh">

    <div class="container-default d_flex justify_between p_t_20">

        <div>
          <img src="../assets/img/work-element/dark-logo.png" alt="logo MaxCoach" class="">
        </div>

        <ul class="listTypeNone d_flex flex_row align_center">
            <li class="d_flex text_capital flex_row p-x-10 align_center dropdown">
                <a class="text_decoration p-x-5" href="#">home</a>
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
                <i class="fa-solid fa-cart-shopping"></i>
            </li>
            <li class="d_flex text_capital flex_row p-x-10 align_center">  
                <i class="fa-solid fa-user"></i>
            </li>
            <li id="search" class="d_flex text_capital flex_row p-x-10 align_center b_rounded_1">
                <input type="text" placeholder="Search..." class="b_none">
                <i class="fa-solid fa-magnifying-glass"></i>
            </li>
        </ul>

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
        background-image: url('../assets/img/general/jumbo-overlay.svg');
    }

    a,
    i {
        color: $blue-logo;
    }

    i {
        cursor: pointer;
    }

    #search {
        background: $white;
        padding: 15px;
    }
 

</style>
