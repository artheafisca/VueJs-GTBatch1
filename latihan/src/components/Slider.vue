<template>
  <div class="px-5 py-5 bg-light">
          <h4>Complete Your Room</h4>
          <h4>With What We Designed</h4>
          <div class="d-flex flex-row justify-content-between py-5">
              <Card v-for="(item, index) in arrCardTittle"
              :key="index" :cardTittle="item" 
              :cardPrice="arrCardPrice[index]"
              :cardImage="arrCardImage[index]"></Card>
          </div>
      </div>
</template>

<script>
import Card from './Card.vue'
export default {
    name        : "SliderComponent",
    components  : { 
        Card 
        },
    data(){
        return{
            arrCardTittle   : ["Cangkir Mauttie", "Saman Kakka", "Lino Dino", "Syail Ammeno"],
            arrCardPrice    : ["89.300.000", "14.500.000", "22.000.000", "12.000.000"],
            arrCardImage    : ["chair-1", "chair-2", "chair-3", "chair-4"]
        };
    }
}
</script>

<style>

</style>