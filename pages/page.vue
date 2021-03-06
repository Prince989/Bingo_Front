<template>
  <div class="baby">
      <div class="container-fluid navbarSh">
        <div class="container">
          <div class="justify-content-around d-flex">
          <ul class="list-inline d-flex first-nav">
            <li><i class="fa fa-user-circle-o" aria-hidden="true"></i><a href="#" class="mr-4 text-decoration-none"> حساب من</a></li>
            <li> <a href="#" class="text-decoration-none"><i class="fa fa-comments" aria-hidden="true"></i> چت های من </a></li>
          </ul>
          <ul class="list-inline text-right d-flex first-nav">
            <li><a href="#" class="text-decoration-none">همه آگهی ها</a></li>
            <li><a href="#" class="ml-4 text-decoration-none">پشتیبانی</a></li>
          </ul>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
  export default {
    name: "page"
  }
</script>

<style scoped>
  .baby{
    font-family: 'B Yekan',serif;
  }
  .navbarSh {
    height: 25px !important;
    background: #d5e2e8;
    border : none;
    border-radius: 0px;
  }
  .first-nav li a{
    color: #828283;
  }
  .first-nav li{
    color: #828283;
  }
  .first-nav li a:hover{
    color: #bf5a18 !important;
    text-decoration: none;
  }
  @media only screen and (max-width: 600px) {
    .navbarSh {
      display: none;
    }
  }
</style>
