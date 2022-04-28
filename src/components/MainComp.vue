<template>

  <div>
    
    <div class="text_center p_50">
        <span class="text_uppercase">start learning coding languages</span>
        <h2 class="text_capital fs_8">build your dream <span class="text_uppercase text_jungle">today</span></h2>
    </div>

    <div id="sec-1" class="container-default d_flex justify_between">
        <div class="flexColAJCenter">
            <img class="" src="../assets/img/work-element/home-5-image-box-01.png" alt="ideas">
            <h4 class="text_capital text_center fs_4">idea discussion</h4>
            <p class="text_center fs_2">
                Get teamed up with the specialist who
                work and teach coding for years at
                famous universities.
            </p>
            <h5 class="text_mulled-wine text_center fs_2" >Start now <i class="text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
        </div>
        <div class="flexColAJCenter">
            <img src="../assets/img/work-element/home-5-image-box-02.png" alt="web">
            <h4 class="text_capital text_center fs_4">web development</h4>
            <p class="text_center fs_2">
                Learn to start building a webpage from scratch.
                You decide your own pace, course and speed.
            </p>
            <h5 class="text_mulled-wine text_center fs_2" >Start now <i class="text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
        </div>
        <div class="flexColAJCenter">
            <img src="../assets/img/work-element/home-5-image-box-03.png" alt="systems">
            <h4 class="text_capital text_center fs_4">system administration</h4>
            <p class="text_center fs_2">
                Learners are encouraged to study the mechanism and structure of system
                administration.  
            </p>
            <h5 class="text_mulled-wine text_center fs_2" >Start now <i class="text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
        </div>
        <div class="flexColAJCenter">
            <img src="../assets/img/work-element/home-5-image-box-04.png" alt="graphics">
            <h4 class="text_capital text_center fs_4">graphic design</h4>
            <p class="text_center fs_2">
                Have a passion for graphics and arts?
                Show your talents with confidence and 
                self-assertiveness.
            </p>
            <h5 class="text_mulled-wine text_center fs_2" >Start now <i class="text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
        </div>
    </div>

    <div class="container-default">
        <div></div>
        <div>
            <div class="text_center p_50">
                <span class="text_uppercase">dream with <span class="fw_b">maxcoach</span></span>
                <h2 class="text_capital fs_8">construct a <span class="text_capital text_jungle">stunning</span> career perspective</h2>
            </div>
            <div class=" dropdown">
                <h4 id="drop" class="text_white bg-jungle-green b_rounded_1">
                    <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                    <i class="text_white p_s_20 fa-solid fa-circle-minus"></i>
                </h4>
                <div class="dropdown-content">
                    <p></p>
                </div>
            </div>
            
            
        </div>
    </div>

  </div>

</template>

<script>

export default {
  name: 'MainComp',
  components: {
  
  }
}
</script>

<style lang="scss">
@import '../assets/style/general.scss';

    #sec-1 h5 {
        cursor: pointer;
    }

    #drop {
        @include paddingButton;
    }
   

</style>
