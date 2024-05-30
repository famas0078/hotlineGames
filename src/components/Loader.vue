<template>
    <div v-if="loading" class="loader">
      <span class="loader"></span>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        loading: true
      };
    },
    mounted() {
      setTimeout(() => {
        this.loading = false;
      }, 3000);
    }
  };
  </script>
  
  <style>
  .loader {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: var(--color-back);
    z-index: 9999;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  </style>