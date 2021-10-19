<template>
  <div class="header-main-container">
    <div class="header-navbar-items col-md-12 col-sm-12 col-xs-12">
      <b-navbar toggleable="lg">
        <div class="abn-amro-logo-container col-md-4 col-sm-4 col-xs-4">
          <img
            src="../assets/abn-amrro.png"
            alt=""
            class="d-inline-block align-text-top abn-amro-logo"
          />
          <div class="back-to-page">
            <div class="left-icon">
              <i class="bi bi-chevron-compact-left left_icon"></i>
            </div>
            <div class="user-path">
              <span>abnamro.nl</span>
            </div>
          </div>
        </div>

        <b-navbar-toggle
          target="nav-collapse"
          class="collapse-button"
        ></b-navbar-toggle>
        <b-collapse class="navbar-collapse-container" id="nav-collapse" is-nav>
          <b-navbar-nav class="col-md-8">
            <b-nav-item class="second-navbar-item">
              <div class="user-login-details">
                <span>Laastste login:</span><span>6 september 2017, 15:33</span>
              </div>
            </b-nav-item>
          </b-navbar-nav>
          <b-navbar-nav class="col-md-4">
            <b-nav-item class="third-navbar-item">
              <div class="user-login-container">
                <div class="user-login-status">
                  <span class="user-name"> E. Rozenhart Uitloggen</span>
                </div>
                <div class="person-icon">
                  <span class=" bi-person-square"></span>
                </div>
              </div>
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <Search />
  </div>
</template>
<script>
import Search from "./Search.vue";
export default {
  name: "Header",
  components: {
    Search,
  },
};
</script>
<style scoped>
img.d-inline-block.align-text-top.abn-amro-logo {
  width: 80px;
  height: 52px;
}
.abn-amro-logo-container.col-md-4 {
  display: flex;
  padding-left: 60px;
}
li.form-inline {
  padding-left: 62px;
}

.back-to-page {
  display: flex;
  margin-top: 11px;
}
a.nav-link {
  display: flex;
}
.user-login-details {
  display: contents;
}
.user-login-container {
  display: contents;
}
/* .navbar-collapse-container {
  padding-left: 120px;
} */
.person-icon {
  padding-left: 6px;
}
i.bi.bi-chevron-compact-left.left_icon {
  color: #0d8b5c;
}
.user-path {
  color: #0d8b5c;
}
</style>
