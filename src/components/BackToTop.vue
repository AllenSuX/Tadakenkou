<template>
    <div v-show="isVisible" @click="scrollToTop" class="scroll-to-top">
      
    </div>
  </template>
  
  <script setup>
  import { ref, onMounted, onUnmounted } from 'vue';
  
  const isVisible = ref(false);
  
  const scrollToTop = () => {
    window.scrollTo({
      top: 0,
      behavior: 'smooth'
    });
  };
  
  const handleScroll = () => {
    isVisible.value = window.scrollY > window.innerHeight;
  };
  
  onMounted(() => {
    window.addEventListener('scroll', handleScroll);
  });
  
  onUnmounted(() => {
    window.removeEventListener('scroll', handleScroll);
  });
  </script>
  
  <style scoped>
  .scroll-to-top {
    position: fixed;
    background-image: url(.//icons/arrow-bar-up.svg);
    background-repeat: no-repeat;
    background-size: contain;
    bottom: 20px;
    right: 20px;
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    cursor: pointer;
    /* box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2); */
    transition: opacity 0.3s ease-in-out;
    z-index: 999999;
  }
  .scroll-to-top:hover{
    animation: moveUpDown 0.5s infinite alternate;
  }
  @keyframes moveUpDown{
    0% {
        transform: translateY(0);
    }
    100% {
        transform: translateY(-10px);
    }
  }
  </style>
  