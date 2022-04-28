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

    <div class="container-default flexBetween_2 p-y-50 ">
        <div>
            <img src="../assets/img/work-element/about-us-03-image-01.png" alt="">
        </div>
        <div class="d_flex flex_col w_50">
            <div class="text_start">
                <span class="text_uppercase">dream with <span class="fw_b">maxcoach</span></span>
                <h2 class="text_capital fs_8">construct a <span class="text_capital text_jungle">stunning</span> career perspective</h2>
            </div>
            <div class="justify_start">
                <div class=" dropdown">
                    <h4 id="drop" class="text_white bg-jungle-green b_rounded_1">
                        <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                        <i class="text_white p_s_20 fa-solid fa-circle-minus"></i>
                    </h4>
                    <div class="dropdown-content">
                        <p>
                            MaxCoach supports the act of teaching and learning on multiple
                            platforms like online or offline via meterial downloads.
                            We know things aren't supposed to be devoured in a short time, you
                            can always access our knowledge base from any device.
                        </p>
                    </div>
                </div>
                <div class=" dropdown">
                    <h4 id="drop" class="text_white bg-jungle-green b_rounded_1">
                        <span class="text_capital">multiple course partecipation </span>at the <span class="text_capital">same time</span>
                        <i class="text_white p_s_20 fa-solid fa-circle-minus"></i>
                    </h4>
                    <div class="dropdown-content">
                        <p>
                            
                        </p>
                    </div>
                </div>
                <div class=" dropdown">
                    <h4 id="drop" class="text_white bg-jungle-green b_rounded_1">
                        <span class="text_capital">track study progress & deliver prompt feedback </span>
                        <i class="text_white p_s_20 fa-solid fa-circle-minus"></i>
                    </h4>
                    <div class="dropdown-content">
                        <p>
                            
                        </p>
                    </div>
                </div>
            </div>
            
        </div>
    </div>

    <div id="divider" class="p_50 bg-gallery flexRowWrap">
        <div class="container-default flexBetween">
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">1.926</span>
                <div class="text_uppercase fw_b">finished sessions</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">3.092+</span>
                <div class="text_uppercase fw_b">enrolled learners</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">200</span>
                <div class="text_uppercase fw_b">online instructors</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">100%</span>
                <div class="text_uppercase fw_b">satisfaction rate</div>
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

    #divider {
        height: 150px;
    }
   

</style>
