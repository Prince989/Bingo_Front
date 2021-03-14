<template>
  <div>
    <div class="headerbt-m">
      <input type="text" class="form-control bg-light text-right" placeholder="...جستجو">
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
    height: 45px;
    color: rgba(234, 248, 255, 0.85);
    box-shadow:1px 0.1px 5px rgba(78, 85, 91, 0.19);
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
  .addbtn {
    border-radius: 16px;
    margin-top: auto;
    margin-bottom: auto;
    font-size: smaller;
    background-color: #0084ff;
  }
</style>
