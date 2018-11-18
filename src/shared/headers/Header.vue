<template>
   <div class="nav-bar mb-3">
    <nav class="navbar navbar-expand-lg nav-custom navbar-light bg-light static-top">
        <div class="container">
            <router-link class="navbar-brand" to="/">
                <!-- <img src="http://placehold.it/150x50?text=Logo" alt=""> -->
                <i class="ion-ios-appstore"></i>
                </router-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                  <router-link class="nav-link" to="/login">Register</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/login">Sign In</router-link>
                </li>
                <li>
                   <a href="" class="nav-link"><img alt="Vue logo" src="~@/assets/images/flag.png" height="20"></a>
                </li>
            </ul>
            </div>
        </div>
     </nav>
   </div>
</template>