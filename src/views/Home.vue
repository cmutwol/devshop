<template>
  <div class="home" id="home">
    <div class="row">
      <div class="col-sm-6 col-md-6 col-lg-6">
        <div class="home-search">
          <h3>DevShop</h3>
          <p class="home-p">What would you like to order today ?</p>
            <button type="submit" class="btn cust-btn btn-success">Explore <i class="ion-ios-arrow-round-forward"></i></button>
        </div>
      </div>
      <div class="col-sm-6 col-md-6 col-lg-6 mt-3">
         <img src="~@/assets/images/desktop.png" class="img-fluid"/>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
  }
};
</script>
