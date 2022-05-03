<template>

  <div>
    <!-- Paragrafo cin effetto al click -->
    <div class="justify_start p-y-10">
        
        <div class="bg-custom-white p_10 flexRowWrap align_center b_rounded_1" style="width: 450px" v-if="isActive" >  
            <h4 class="">
                <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
            </h4>
            <i class="p_s_20 fa-solid fa-circle-plus fs_3 pewter" @click="getShowAct()"></i>
        </div>    
        <div v-if="active" class="bg-jungle-green p_10 flexRowWrap align_center text_white b_rounded_1" style="width: 450px">
            <h4 class="">
                <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
            </h4>
            <i class="p_s_20 fa-solid fa-circle-minus fs_3" @click="getShowIsAct()"></i>
        </div>

        <div v-if="active" class="bg-custom-white p_10" style="width: 450px">
            <p class="p_20 b_rounded_1">
                MaxCoach supports the act of teaching and learning on multiple
                platforms like online or offline via meterial downloads.
                We know things aren't supposed to be devoured in a short time, you
                can always access our knowledge base from any device.
            </p>
        </div> 

    </div>
            
</div>

</template>

<script>

export default {
  name: 'ShowHideComp',
  components: {
      
  },

  data() {
      return {
        active: false,
        isActive: true,
        counter: 0,
      }
  },

  methods: {
      getShowAct(index) {
          console.log(index);
        if(!this.active == true & !this.isActive == false){
            this.active = true;
            this.isActive = false;
        }  else {
            this.active = false
            this.isActive = true;
        } return
    },

    getShowIsAct(i) {
        console.log(i)
        if(this.isActive == false & this.active == true){
            this.isActive = true;
            this.active = false;
        }  else {
            this.isActive = false;
            this.active = true;
        } return
    },

     // Funzione che riconosce l'index dell'elemento ciclato
    // e al click sul tag <li> cambia l'index,
    // e inserendola nel tag img della chat di destra
    // mi restituisce l'indice cliccato stampandolo a video
    lookIndex: function(indexClick){
        console.log(indexClick);
        this.counter = indexClick;
        console.log(`l'index cliccato è: ${this.counter}`);
    },

  }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/general.scss';

    

</style>
