<template>
    <div class="scroll-nav">
    <!-- <nav class="navbar navbar-expand-lg navbar-dark bg-dark"> -->
    <nav class="navbar navbar-expand-md navbar-light fixed-top bg-light cust-nv">
      <button class="navbar-toggler" type="button" data-toggle="collapse" 
        data-target="#navbarsExample08" aria-controls="navbarsExample08" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-md-center" id="navbarsExample08">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#"> <h5>DevShop</h5></a>
          </li>
          <li class="nav-item">
            <form class="form-inline cust-input-group">
              <!-- <input class="form-control input-group-sm nav-search" type="text" placeholder="Search"> -->
              <div class="input-group">
                  <div class="input-ico">
                      <div class="input-group-prepend">
                          <span class="input-group-text" id="basic-addon1"><i class="ion-ios-search"></i></span>
                      </div>
                  </div>
                  <input type="text" spellcheck="false" class="cust-search" placeholder="Search...">
              </div>
            </form>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Software</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Software</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Software</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Software</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Software</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="https://example.com" id="dropdown08" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</a>
            <div class="dropdown-menu" aria-labelledby="dropdown08">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
           <li class="nav-item">
             <a class="nav-link disabled" href="#">
               <i class="ion-ios-cart cust-cart"></i>
               <span class="badge badge-pill badge-warning">0</span>
           </a>
          </li>
        </ul>
      </div>
    </nav>
    </div>
</template>
<style lang="scss" scoped>
    
</style>
