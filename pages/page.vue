<template>
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="#">WebSiteName</a>
      </div>
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Page 1 <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Page 1-1</a></li>
            <li><a href="#">Page 1-2</a></li>
            <li><a href="#">Page 1-3</a></li>
          </ul>
        </li>
        <li><a href="#">Page 2</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
        <li><a href="#"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
      </ul>
    </div>
  </nav>

</template>

<script>
  export default {
    name: "page"
  }
</script>

<style scoped>
  .navbar {
    height: 30px;
    font-size:15px;
    //WhatAreYou
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


