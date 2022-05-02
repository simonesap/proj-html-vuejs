<template>

  <div class="">

    <VueSlickCarousel class="" :key="el" :arrows="true" :dots="true" v-bind="slickOptions">
      <div v-for="el in 4" :key="el">
     
        <ul id="slick-ul-1" class="flexBetween align_center">
          
          <li class="p_100 justify_end d_flex flex_col"
                v-for="(element,index) in mediaCardArray" :key="index">
            <div class="d_flex justify_center p_relative">
              <img class="img-circle b_rounded_circle p_absolute m_t_100" 
                  :src="element.img" alt=""> 
            </div>
            
            <div id="back" class="p_50 m_t_100">
              <p class="m_t_100  p_relative text_center">
                  {{element.description}}
              </p>
              <h4 class="text_uppercase text_center">{{element.name}}</h4>
              <div class="text_capital text_center">{{element.position}}</div>
            </div>
          </li>
        </ul>
        
      </div>
     
    </VueSlickCarousel>
   
  </div>

</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'


export default {
  name: 'SlickComp',

    data() {
        return {
            slickOptions: {
                slidesToShow: 1,
                slidesToScroll: 1,
                autoplay: true,
                arrows: false,
                autoplaySpeed: 5000,
                pauseOnFocus: true,
                pauseOnHover: true,
                pauseOnDotsHover: true,
            },
            counterImg: 0,
            mediaCardArray: [
            {
                name: 'mina hollace',
                img: require('../assets/img/work-element/testimonial-avata-02.jpg'),
                description: 'I am free to learn at my own pace, follow my own schedule and choosethe subject like. Great study portal for people like me.',
                position: '/ Freelancer',
            },
            { 
                name:'madley pondor',
                img: require('../assets/img/work-element/testimonial-avata-04.jpg'),
                description:'MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.',
                position: '/ IT specialist',
            },
            { 
                name: 'luvic dubble',
                img: require('../assets/img/work-element/testimonial-avata-01.jpg'),
                description: 'I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.',
                position: '/ private tutor',
            },
          ]
         } 
        
    },

    components: {
        VueSlickCarousel,
  },

  created() {
        
        },

        methods: {
    
        }
}
</script>

<style lang="scss" scoped>
@import 'vue-slick-carousel/dist/vue-slick-carousel.css';
  // optional style for arrows & dots
@import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css';
@import '../assets/style/general.scss';

    #slick-ul-1 {
        @include reset-list
    }

    #slick-ul-1 li{
        width: calc((100% / 3) - 15px);
        padding: 20px;
        height: 400px;
    }

    .img-circle {
      margin-top: -100px;
      justify-self: center;
      width: 150px;
      height: 150px;
    }

    #back {
      background-color: $white;
      width: 250px;
      height: 200px
    }

    .justify_end {
      @include justifyEnd;
    }

</style>