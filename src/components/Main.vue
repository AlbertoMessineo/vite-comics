<script>
import Cards from './Cards.Vue';
export default {
  name: 'Main',
  components: {
    Cards,
  },
};
</script>
<template>
  <main>
      <div class="up">
        <div class="bg-img">

        </div>
        <div class="container">
          <Cards />
        </div>
      
      </div>
      <div class="center">
        <div class="container">
          <ul>
           <li>
            <img src="/src/assets/img/buy-comics-digital-comics.png" alt="">
            <span>Digital Comics</span>
           </li>
           <li>
            <img src="/src//assets/img/buy-comics-merchandise.png" alt="">
            <span>Dc merchandise</span>
           </li>
           <li>
            <img src="/src/assets/img/buy-comics-shop-locator.png" alt="">
            <span>subscription</span>
           </li>
           
           <li>
            <img src="/src/assets\img/buy-comics-subscriptions.png" alt="">
            <span>comic shop locator</span>
           </li>
           
           <li>
            <img src="/src/assets/img/buy-dc-power-visa.svg" alt="">
            <span>Dc power visa</span>
           </li>
          </ul>
        </div>
      </div>
      <div class="down">
        <div class="container">ad cs</div>
      </div>
    
  </main>
</template>
<style></style>