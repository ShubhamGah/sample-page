<template>
  <div class="pricing-details">
    <!-- pricing-details card 1 -->
    <div class="card">
      <div class="card-body-two mt-4 pb-4">
        <div class="details-header col-md-12 col-xs-12 col-sm-12">
          <span class="title-heading">
            <h3><b>Uitkeing</b></h3></span
          >
        </div>
        <div class="row items-details col-md-12 col-xs-12 col-sm-12  ">
          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Datum volgenen Uitkeing</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2 ">
            <span>03-10-2020</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Datum laaste Uitkeing</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>03-05-2022</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>Vaste rente</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>0,40%</span>
          </div>
        </div>
      </div>
    </div>
    <!-- card two -->
    <div class="card card-two">
      <div class="card-body-two mt-4 pb-4">
        <div class="row items-details col-md-12 col-xs-12 col-sm-12">
          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>Bruto Uitkeing per maad</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>&euro;1080,94</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Kosten per Uitkeing</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>- &euro; 2,50</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Ingehouden loonheffing</span>
            <b-icon
              icon="exclamation-circle"
              class="exclamation-circle"
            ></b-icon>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>220,16</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Bijdrage zonhkscbiwecbwuie </span>
            <b-icon
              icon="exclamation-circle"
              class="exclamation-circle"
            ></b-icon>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>- &euro; 94,30</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>lokkcnowicwecnowc </span>
            <b-icon
              icon="exclamation-circle"
              class="exclamation-circle"
            ></b-icon>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>Nee</span>
            <b-icon icon="pencil" class="pencil-icon"></b-icon>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6">
            <span>Vriknwocnwecwe c</span>
            <b-icon
              icon="exclamation-circle"
              class="exclamation-circle"
            ></b-icon>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>Nee</span>
            <b-icon icon="pencil" class="pencil-icon"></b-icon>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>CAK c</span>
            <b-icon
              icon="exclamation-circle"
              class="exclamation-circle"
            ></b-icon>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span>Ja</span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 "></div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span><hr /></span>
          </div>

          <div class="datum-vol col-md-6 col-xs-6 col-sm-6 ">
            <span>Uw Uitkeing per maad</span>
          </div>
          <div class="datum-vol-item col-md-6 col-xs-6 col-sm-6 pb-2">
            <span
              ><h3>&euro; 763,<sup>98</sup></h3></span
            >
          </div>

          <div class="neem-contact col-md-12 col-xs-12 col-sm-12 mt-2 ">
            <span>Alle transicties schijes we af van uw Leefrententeeking</span>
            <div class="next-page-nav">
              <div class="right-icon">
                <i class="bi bi-chevron-compact-right"></i>
              </div>
              <div class="user-path">
                <span>Neem contact met ons op</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "PricingDetails",
};
</script>
<style scoped>
.card {
  margin-left: 30px;
  margin-right: 29px;
}
.card.card-two {
  margin-left: 30px;
  margin-right: 29px;
  background-color: #eff8f861;
}
.card.card-body {
  display: flow-root;
}
/* .row.items-details {
  display: inline-block;
} */
.card-body-two {
  text-align: justify;
  padding-left: 20px;
}

.exclamation-circle {
  width: 23px;
  height: 18px;
  padding-left: 6px;
}
.bi-pencil.pencil-icon.b-icon.bi {
  width: 18px;
  margin-left: 8px;
  color: #0d8b5c;
}
.next-page-nav {
  display: flex;
}
.neem-contact.col-md-6 {
  width: 100%;
}
.datum-vol.col-md-6 {
  color: #0d8b5c;
}
.user-path {
  color: #0d8b5c;
}
</style>
