<template>
  <div id="badges">
    <div class="row">
      <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
        <div class="idb-block">
          <div class="idb-block-title">
            <h4>Badge Size</h4>
          </div>
          <div class="idb-block-content">
            <div class="heading">
              <h1>h1. Bootstrap heading <b-badge>New</b-badge></h1>
              <h2>h2. Bootstrap heading <b-badge variant="primary">New</b-badge></h2>
              <h3>h3. Bootstrap heading <b-badge variant="warning">New</b-badge></h3>
              <h4>h4. Bootstrap heading <b-badge variant="danger">New</b-badge></h4>
              <h5>h5. Bootstrap heading <b-badge variant="info">New</b-badge></h5>
              <h6>h6. Bootstrap heading <b-badge variant="success">New</b-badge></h6>
            </div>
          </div>
        </div>
        <div class="idb-block">
          <div class="idb-block-title">
            <h4>Badges Color</h4>
          </div>
          <div class="idb-block-content">
            <div class="badge-style">
              <b-badge variant="primary">Primary</b-badge>
              <b-badge variant="warning">Warning</b-badge>
              <b-badge variant="danger">Danger</b-badge>
              <b-badge variant="info">Info</b-badge>
              <b-badge variant="success">Success</b-badge>
              <b-badge variant="secondary">Secondary</b-badge>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'badges'
}
</script>
