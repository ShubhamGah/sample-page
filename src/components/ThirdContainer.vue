<template>
  <div class="third-container">
    <div class="card">
      <div class="card-body-two mt-4 pb-4">
        <div class="tregenke-card-header">
          <div class="col-md-10">
            <span>
              <h3><b>Tregenkening</b></h3></span
            >
          </div>
          <div class="col-md-2 wijzigen-container">
            <b-icon icon="pencil" class="pencil-icon"></b-icon>
            <span class="wij">wijzigen</span>
          </div>
        </div>
        <div class="row items-details col-md-12">
          <div class="col-md pb-2">
            <div class="datum-vol col-md-6">
              <span>U ontdewib uw niwec </span>
            </div>
            <div class="datum-vol-item col-md-6">
              <span>NL ABNA 8709 0289 07</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ThirdContainer",
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

.row.items-details {
  display: inline-block;
}
.card-body-two {
  text-align: justify;
  padding-left: 52px;
}

.bi-pencil.pencil-icon.b-icon.bi {
  width: 18px;
  margin-left: 8px;
}

.tregenke-card-header {
  display: flex;
}
.pencil-icon {
  color: #0d8b5c;
}
.wij {
  color: #0d8b5c;
  padding-left: 12px;
}
</style>
