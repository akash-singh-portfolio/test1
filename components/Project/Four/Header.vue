<template>
  <header class="header-project4 bg-img d-flex align-items-end" data-background="/assets/imgs/works/projects/1/1.jpg"
    data-overlay-dark="3">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="caption text-center">
            <h1>Technology Process</h1>
          </div>
        </div>
      </div>
      <div class="info mt-80 pt-50 bord-thin-top">
        <div class="row">
          <div class="col-md-6 col-lg-3">
            <div class="item mb-30">
              <span class="opacity-8 mb-5">Category :</span>
              <h6>Development</h6>
            </div>
          </div>
          <div class="col-md-6 col-lg-3">
            <div class="item mb-30">
              <span class="opacity-8 mb-5">Client :</span>
              <h6>Envato</h6>
            </div>
          </div>
          <div class="col-md-6 col-lg-3">
            <div class="item mb-30">
              <span class="opacity-8 mb-5">Start Date :</span>
              <h6>7 August 2023</h6>
            </div>
          </div>
          <div class="col-md-6 col-lg-3">
            <div class="item">
              <span class="opacity-8 mb-5">Designer :</span>
              <h6>UiCamp</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import { onMounted } from 'vue';
//= Scripts
import loadBackgroudImages from '@/common/loadBackgroudImages';

onMounted(() => {
  loadBackgroudImages();
});
</script>