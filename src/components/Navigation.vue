<template>
  <div class="navigation-main-container">
    <div class="back-navigation-contaienr">
      <div class="user-path-container mt-2">
        <div class="left-icon pb-1">
          <i class="bi bi-chevron-compact-left"></i> Terug
        </div>
        <div class="user-path">
          <span class="page-title">Leefrente</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Navigation",
};
</script>
<style scoped>
.navigation-main-container {
  background-color: #005e5d;
  color: #ffff;
}
.back-navigation-contaienr {
  display: table-caption;
  margin: 29px;
  padding-left: 18px;
}
.left-icon {
  display: flex;
}
.user-path {
  padding-left: 3px;
}
</style>
