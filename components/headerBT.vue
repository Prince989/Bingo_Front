<template>
  <div>
    <div class="row headerbt-m">
      <button class="btn chatbtn text-secondary col-3"><i class="fa fa-comments" style=""></i></button>
      <div class="searchbar form-group text-right row flex-wrap d-flex flex-row align-items-center mr-1 col-9 mt-1">
        <span class="col-1 p-1 d-flex mr-auto text-left mt-2">
        <i class="fas fa-map-marker-alt text-secondary col-6 mr-auto marker"></i>
        <label class="text-secondary col-6 text-nowrap"
               style="font-size: 14px!important;">همه ایران</label>
          </span>
        <input type="text" class="form-control text-right bg-transparent ml-auto mt-auto mb-auto w-auto col-9 " placeholder="...جستجو">
        <button class="btn bar pr-0 col-2 ml-auto"><i class="fas fa-bars text-secondary  mt-1 "></i></button>
      </div>
    </div>
    <div class="headerbt">
      <div class="container h-100 d-flex align-items-center pr-5 pl-5">
        <button class="btn btn-info addbtn d-flex align-items-center" style="font-size: medium"> ثبت آگهی رایگان &nbsp;
          &nbsp;<i
            class="fas fa-plus"></i></button>
        <img src="@/static/Bingo.png" class="d-flex ml-auto" width="120" height="120">
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "headerBT"
  }
</script>

<style scoped>
  .headerbt {
    height: 55px;
    color: rgba(234, 248, 255, 0.85);
    box-shadow: rgba(78, 85, 91, 0.22) 1px 1px 1px 0.8px;
  }

  .headerbt-m {
    height: 60px;
    color: rgba(234, 248, 255, 0.85);
    box-shadow: 1px 0.1px 5px rgba(78, 85, 91, 0.19);
  }

  @media only screen and (max-width: 600px) {
    .headerbt {
      display: none;
    }
  }

  @media only screen and (min-width: 601px) {
    .headerbt-m {
      display: none;
    }
  }

  .searchbar {
    background-color: #eeeeee;
    box-shadow: none;
    border-radius: 7px;
    height: 85%;
  }

  .searchbar input {
    border: none;
    background: none;
    outline: none;
    padding: 0;
    font-size: 12px;
  }

  .searchbar input:focus {
    outline: none;
    box-shadow: none;
  }

  .addbtn {
    border-radius: 16px;
    margin-top: auto;
    margin-bottom: auto;
    font-size: smaller;
    background-color: #0084ff;
  }
  .marker{
    font-size:19px;
  }
  .bar{
    font-size:19px;
  }
  .chatbtn {
    font-size: 22px;
  }
</style>
