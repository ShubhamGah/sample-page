<template>
  <div class="page-details-container">
    <!-- Leefrententeeking container -->
    <div class="pricing-details-container1 col-md-8">
      <div class="first-container">
        <FirstContainer />
        <PricingDetails />
        <ThirdContainer />
        <Document />
        <Contact />
      </div>
      <!-- wat geberut detarils -->
      <div class="wat-geberut-container col-md-8 col-xs-8 col-sm-8">
        <div class="links-container mt-5">
          <div class="arrange-data-container col-md-12 col-xs-12 col-sm-12">
            <span class="title-heading"
              ><h4><b>Wat geberut er als...?</b></h4></span
            >
          </div>
          <div class="container-details mt-2 col-md-12 col-xs-12 col-sm-12">
            <div class="details-one">
              <span
                >Gaat u ventuirsed naar het buiteds? Of with u wetern newciweno
                iwedwqed nowee cwecwe ncowecnweobwfc</span
              >
            </div>
            <div class="back-to-contact-two mt-2 col-md-12 col-xs-12 col-sm-12">
              <div class="user-path-two">
                <span>Als er iets verander in uw sitere</span>
              </div>
              <div class="right-icon">
                <i class="bi bi-chevron-compact-right"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Zelf regelen container -->
    <div class="pricing-details-container2 col-md-4 col-sm-4 col-xs-4">
      <div class="links-container mt-5">
        <div class="arrange-data-container col-md-12 col-sm-12 col-xs-12">
          <span class="title-heading"
            ><h4><b>Zelf regenlen</b></h4></span
          >
        </div>
        <div class="links-table col-md-12 col-sm-12 col-xs-12">
          <table class="details-links-table col-md-12 col-sm-12 col-xs-12">
            <tr class="table-row-one">
              <th class="first-link-arrow">
                <i class="bi bi-arrow-right"></i>
              </th>
              <th class="first-link details">
                <span>Bij-en afresffoefn bekinjken</span>
              </th>
            </tr>
            <tr class="table-row-two">
              <th class="second-link-arrow">
                <i class="bi bi-arrow-right"></i>
              </th>
              <th class="second-link details"><span>Loonsjdniwcbwoic</span></th>
            </tr>
            <tr class="table-row-three">
              <th class="third-link-arrow">
                <i class="bi bi-arrow-right"></i>
              </th>
              <th class="third-link details"><span>Vriiodne oneveor</span></th>
            </tr>
          </table>
        </div>
      </div>
    </div>
    <!-- Heeft u een vraag container -->
    <div class="pricing-details-container3 col-md-4 col-sm-4 col-xs-4">
      <div class="heeft-container">
        <div class="heet-text-container col-md-12 col-sm-12 col-xs-12">
          <span class="title-heading"
            ><h4><b>Heeft u een vraag?</b></h4></span
          >
        </div>
        <div class="heeft-image-container">
          <img src="../assets/contact-us.png" class="contact-us-image" alt="" />
        </div>
        <div class="contact-text-container col-md-12 col-sm-12 col-xs-12">
          <span>Neem contact met ons, we help u graag</span>
        </div>
        <div class="back-to-contact">
          <div class="right-icon col-md-2 col-sm-2 col-xs-2">
            <i class="bi bi-chevron-compact-right"></i>
          </div>
          <div class="user-path col-md-12 col-sm-12 col-xs-12">
            <span>Neem contact met ons op</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import FirstContainer from "./FirstContainer.vue";
import PricingDetails from "./PricingDetails.vue";
import ThirdContainer from "./ThirdContainer.vue";
import Document from "./Documenten.vue";
import Contact from "./Contact.vue";
export default {
  name: "PageDetails",
  components: {
    FirstContainer,
    PricingDetails,
    ThirdContainer,
    Document,
    Contact,
  },
};
</script>
<style scoped>
.page-details-container {
  display: inline-block;
  background-color: #f3f3f3;
  width: 100%;
}
.pricing-details-container1 {
  /* height: 1426px; */
  float: left;
  background-color: #f3f3f3;
}
.pricing-details-container2 {
  height: 220px;
  float: left;
  background-color: #f3f3f3;
  padding-left: 31px;
}
.pricing-details-container3 {
  height: 180px;
  float: left;
  background-color: #f3f3f3;
  padding-left: 31px;
}
.heeft-image-container {
  float: left;
}
img.contact-us-image {
  height: 32px;
  width: 38px;
}
.back-to-contact {
  display: inline-flex;
}
.details {
  text-align: initial;
}
.card {
  margin-top: 22px;
  margin-left: 44px;
  margin-right: 15px;
}
.links-container.mt-5 {
  height: 177px;
}
.back-to-contact-two {
  display: inline-flex;
}
.arrange-data-container {
  display: flex;
}
.container-details {
  text-align: start;
}

.wat-geberut-container.col-md-8 {
  margin-left: 25px;
}
.heeft-container {
  text-align: justify;
}
i.bi.bi-arrow-right {
  color: #0d8b5c;
}
.details-links-table th span {
  color: #0d8b5c;
}
.right-icon {
  color: #0d8b5c;
}
.user-path {
  color: #0d8b5c;
}
.user-path-two {
  color: #0d8b5c;
}
</style>
