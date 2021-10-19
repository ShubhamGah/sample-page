<template>
  <div class="contact-container">
    <div class="card">
      <div class="card-body-two mt-4 pb-4">
        <div class="details-header col-md-12 col-sm-12 col-xs-12">
          <span class="title-heading">
            <h3><b>Contactgegevens</b></h3></span
          >
        </div>
        <div class="row items-details col-md-12">
          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Op naaam van</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>E.Rozenhart</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Ingangsdatum</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>03-06-2017</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Looptijd</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>5 Jaar</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>Leefrententeeking</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>NL00 ABNA 1234 5678 90</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>Contactnummer</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>12345678</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contact",
};
</script>
<style scoped>
.datum-vol.col-md-6 {
  color: #0d8b5c;
}

.card {
  margin-top: 22px;
  margin-left: 30px;
  margin-right: 29px;
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
.card-body-two {
  text-align: justify;
  padding-left: 20px;
}
.col-md.pb-2 {
  display: flex;
}
</style>
