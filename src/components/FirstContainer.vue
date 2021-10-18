<template>
  <div class="first-container pb-4">
    <div class="card">
      <div class="card-body">
        <div class="leefrent-img-container col-md-2">
          <img src="../assets/table.jpg" alt="table_img" class="leefren-img" />
        </div>
        <div class="leef-main-text col-md-8">
          <div class="leeftren-text"><b>Leefrententeeking</b></div>
          <div class="leeftren-abn-text">NL00 ABNA 1234 5678 90</div>
        </div>
        <div class="leeftren-pricing-text col-md-2">
          <b>&euro; 21.660,<sup>58</sup></b>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "FirstContainer",
};
</script>
<style scoped>
.card {
  margin-top: 22px;
  margin-left: 44px;
  margin-right: 15px;
}

.card.card-body {
  display: flow-root;
}

.leefrent-img-container.col-md-1 {
  float: left;
}
img.leefren-img {
  height: 32px;
}
.leef-main-text.col-md-8 {
  float: left;
  text-align: justify;
}
.leeftren-pricing-text.col-md-2 {
  float: left;
}
.leefrent-img-container.col-md-2 {
  float: left;
}
</style>
