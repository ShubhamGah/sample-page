<template>
  <div class="search-main-cantainer">
    <div class="header-search-container col-md-12 col-sm-12 col-xs-12">
      <b-navbar toggleable="lg">
        <b-collapse class="navbar-collapse-container" id="nav-collapse" is-nav>
          <b-navbar-nav
            class="col-md-12 col-sm-12 col-xs-12 search-nav-container"
          >
            <b-navbar-item name="one" class="search--navbar-item1 services"
              ><div class="billing-container col-md-2 col-sm-2 col-xs-2 ">
                <i class="bi bi-credit-card"></i> Rekeninge
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item2 services"
              ><div class="zelf-container col-md-2 col-sm-2 col-xs-2">
                <i class="bi bi-pencil-square"></i> Zelf regelen
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item3 services"
              ><div class="bank-mail-container col-md-2 col-sm-2 col-xs-2">
                <i class="bi bi-envelope"></i> Bankmail
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item4 services">
              <div class="bank-mail-container col-md-2 col-sm-2 col-xs-2">
                <i class="bi bi-gear"></i> Instellingn
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item5 services">
              <div class="bank-mail-container col-md-2 col-sm-2 col-xs-2 ">
                <i class="bi bi-slash-square"></i> Takenlijst
              </div></b-navbar-item
            >
            <b-navbar-item class="col-md-2 col-sm-2 col-xs-2 search-input"
              ><div class="col-md-10 col-sm-10 col-xs-10">
                <i class="bi bi-search"></i>
                <input
                  type="text"
                  class="form-control"
                  placeholder="Zoeken"
                  aria-label="Username"
                  aria-describedby="basic-addon1"
                /></div
            ></b-navbar-item>
          </b-navbar-nav>
          <!-- <b-navbar-nav class="search-nav ">
            <b-nav-item class="search-input-navbar-item"> </b-nav-item>
          </b-navbar-nav> -->
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>
<script>
export default {
  name: "Search",
};
</script>
<style scoped>
.services {
  display: contents;
}
.navbar-nav.col-md-8.search-nav-container {
  justify-content: space-evenly;
}
nav-item.search-input-navbar-item {
  padding-left: 32px;
}
.search-main-cantainer {
  background-color: #f9f9f9;
}
input.form-control {
  padding-left: 32px;
}
i.bi.bi-search {
  position: absolute;
  padding-top: 12px;
  padding-left: 5px;
  display: flex;
}
form.form-inline {
  display: flex;
}
.navbar-expand {
  flex-wrap: nowrap;
  justify-content: flex-start;
  padding-left: 80px;
}
</style>
