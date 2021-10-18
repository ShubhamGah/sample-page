<template>
  <div class="document-container">
    <div class="card">
      <div class="card-body-two mt-4 pb-4">
        <div class="tregenke-card-header">
          <div class="col-md-12">
            <span>
              <h3><b>Documenten</b></h3></span
            >
          </div>
        </div>
        <div class="row items-details col-md-12">
          <div class="col-md-12 pb-2">
            <div>
              <b-tabs content-class="mt-3">
                <b-tab title="Overeekenkomst" class="Overeekenkomst">
                  <div class="first-tab-details">
                    <span class="span-one-details">
                      <b-icon
                        icon="file-earmark-ppt-fill"
                        class="pdf-file-icon"
                      ></b-icon
                    ></span>
                    <span>Overeekenkomst leefrent (PDF,12MB)</span>
                  </div>
                  <div class="second-tab-details">
                    <span class="span-one-details">
                      <b-icon
                        icon="file-earmark-ppt-fill"
                        class="pdf-file-icon"
                      ></b-icon
                    ></span>
                    <span>Voorwaeden leefrent (PDF,12MB)</span>
                  </div></b-tab
                >
                <b-tab title="Jaaropgave" class="Jaaropgave"
                  ><p>I'm the second tab</p></b-tab
                >
                <b-tab title="Overige documentaen" class="Overige documentaen"
                  ><p>I'm the third tab</p></b-tab
                >
              </b-tabs>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Document",
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
.tregenke-card-header {
  display: flex;
}
.first-tab-details {
  color: #0d8b5c;
}
.second-tab-details {
  color: #0d8b5c;
}
</style>
