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

<!--<b-container>-->
<!--  <b-navbar toggleable="lg" type="light" variant="light" sticky="true" class="navbar">-->
<!--    <b-navbar-brand href="#">NavBar</b-navbar-brand>-->

<!--    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>-->

<!--    <b-collapse id="nav-collapse" is-nav>-->
<!--      <b-navbar-nav>-->
<!--        <b-nav-item href="#">Link</b-nav-item>-->
<!--        <b-nav-item href="#" disabled>Disabled</b-nav-item>-->
<!--      </b-navbar-nav>-->

<!--      &lt;!&ndash; Right aligned nav items &ndash;&gt;-->
<!--      <b-navbar-nav class="ml-auto">-->
<!--        <b-nav-form>-->
<!--          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>-->
<!--          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>-->
<!--        </b-nav-form>-->

<!--        <b-nav-item-dropdown text="Lang" right>-->
<!--          <b-dropdown-item href="#">EN</b-dropdown-item>-->
<!--          <b-dropdown-item href="#">ES</b-dropdown-item>-->
<!--          <b-dropdown-item href="#">RU</b-dropdown-item>-->
<!--          <b-dropdown-item href="#">FA</b-dropdown-item>-->
<!--        </b-nav-item-dropdown>-->

<!--        <b-nav-item-dropdown right>-->
<!--          &lt;!&ndash; Using 'button-content' slot &ndash;&gt;-->
<!--          <template #button-content>-->
<!--            <em>User</em>-->
<!--          </template>-->
<!--          <b-dropdown-item href="#">Profile</b-dropdown-item>-->
<!--          <b-dropdown-item href="#">Sign Out</b-dropdown-item>-->
<!--        </b-nav-item-dropdown>-->
<!--      </b-navbar-nav>-->
<!--    </b-collapse>-->
<!--  </b-navbar>-->
<!--</b-container>-->
