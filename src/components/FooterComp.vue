<template>

  <div>
    <div class="container-default p_t_100 flexBetween align_center">
        <div>
            <h3 class="text_capital fw_b fs_3">address</h3>
            <ul class="flexColWrap" v-for="(el,index) in footElement[counter].address" :key="index">
                <li class="p-y-10">{{el}}</li>
            </ul>
            <div class="icons p-y-10">
                <ul class="d_flex flex_row">
                    <li class="p_e_35">
                        <a href="https://it-it.facebook.com/" class="fs_5 fa-brands fa-facebook-square"></a>
                    </li>
                    <li class="p_e_35">
                        <a href="https://twitter.com/?lang=it" class="fs_5 fa-brands fa-twitter"></a>
                    </li>
                    <li class="p_e_35">
                        <a href="https://www.instagram.com/" class="fs_5 fa-brands fa-instagram"></a>
                    </li>
                    <li class="p_e_35">
                        <a href="https://it.linkedin.com/" class="fs_5 fa-brands fa-linkedin"></a>
                    </li >
                </ul>
            </div>
        </div>

        <div class="flexRowWrap">
            <div>
                <h3 class="text_capital fw_b fs_3">explore</h3>
                <ul class="d_flex flex_row flex_wrap">
                    <li class="p-y-10 w_35" v-for="(el,index) in footElement[counter].explore" :key="index">
                        <a href="#">{{el}}</a>
                    </li>
                </ul>
            </div>
            <div>
                <h3 class="text_capital fw_b fs_3">information</h3>
                <ul class="flexColWrap" v-for="(el,index) in footElement[counter].information" :key="index">
                    <li class="p-y-10 h_50">
                        <a href="#">{{el}}</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
     
     <div>
         <div class=" text_center">
            <span class="text_capital d_inline vertical_middle">
                
                
            </span>
            <span class="text_end vertical_middle d_inline">
                
            </span>
        </div>

        <div class="p-y-50 flexBetween">
            <div class="colF"></div>
            <div class="colF">
                <img class="vertical_middle" src="../assets/Icons/icons8-diritto-d'autore-16.png" alt=""> 
                2020 maxcoach. all rights reserved
            </div>
            <div class="colF justify_self_end p_20">
                <a href="#" class="fa-solid fa-arrow-up p_15 fs_3 text_white b_rounded_circle bg-jungle-green"></a>
            </div>
            
        </div>
        
            
      
     </div>
    

  </div>

</template>

<script>


export default {
  name: 'FooterComp',
  components: {
    
  },
  data() {
      return {
          counter: 0,
          footElement: [{
              address: ['382 NE 191st St # 87394 Miami, FL 33179-3899',
                       '+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)',
                       'support@maxcoach.com'],
              
              explore: ['Start here',
                         'Blog',
                         'About us',
                         'Success story',
                         'Courses',
                         'Contact us'],
              
              information: ['Memebership',
                            'Purchase guide',
                            'Privacy policy',
                            'Terms of services'],
          }]
          
      }
  },

  methods: {
      getIndex() {

      }
  }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/general.scss';
 
    ul {
        @include reset-list;
    }

    a {
        text-decoration: none;
        color: black;
    }

    .icons {
        ul {
            li {
                a {
                    color: $oslo-gray!important;
                }
            }
        }
    }

    .justify_self_end {
      @include justifySelfEnd;
    }

    
    .vertical-center {
        margin: 0;
        top: 50%;
        -ms-transform: translateY(-50%);
        transform: translateY(-50%);
    }

    #colF {
        flex-basis: calc((100% / 3) - 15px);
    }

</style>
