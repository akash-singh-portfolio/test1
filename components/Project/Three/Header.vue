<template>
  <header class="header-project3 bg-img d-flex align-items-end" data-background="/assets/imgs/works/projects/3/1.jpg"
    data-overlay-dark="9">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="caption">
            <h1>Technology Process</h1>
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