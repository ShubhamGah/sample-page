<template>
  <div class="search-main-cantainer">
    <div class="header-search-container">
      <b-navbar toggleable="lg">
        <!-- <b-navbar-toggle
          target="nav-collapse"
          class="collapse-button"
        ></b-navbar-toggle> -->
        <b-collapse class="navbar-collapse-container" id="nav-collapse" is-nav>
          <b-navbar-nav class="col-md-8 search-nav-container">
            <b-navbar-item name="one" class="search--navbar-item1 services"
              ><div class="billing-container">
                <i class="bi bi-credit-card"></i> Rekeninge
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item2 services"
              ><div class="zelf-container">
                <i class="bi bi-pencil-square"></i> Zelf regelen
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item3 services"
              ><div class="bank-mail-container ">
                <i class="bi bi-envelope"></i> Bankmail
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item4 services">
              <div class="bank-mail-container ">
                <i class="bi bi-gear"></i> Instellingn
              </div></b-navbar-item
            >
            <b-navbar-item name="two" class="search--navbar-item5 services">
              <div class="bank-mail-container ">
                <i class="bi bi-slash-square"></i> Takenlijst
              </div></b-navbar-item
            >
          </b-navbar-nav>
          <b-navbar-nav class="search-nav col-md-4">
            <b-nav-item class="search-input-navbar-item">
              <div>
                <b-navbar type="light">
                  <b-nav-form>
                    <!-- <b-input-group prepend="@">
                      <b-form-input placeholder="Zoeken"
                        ><i class="bi bi-search"></i
                      ></b-form-input>
                    </b-input-group> -->
                    <i class="bi bi-search"></i>
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Zoeken"
                      aria-label="Username"
                      aria-describedby="basic-addon1"
                    />
                  </b-nav-form>
                </b-navbar>
              </div>
            </b-nav-item>
          </b-navbar-nav>
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
  padding-left: 8px;
  padding-top: 6px;
}
form.form-inline {
  display: flex;
}
.navbar-expand {
  flex-wrap: nowrap;
  justify-content: flex-start;
  padding-left: 133px;
}
</style>
