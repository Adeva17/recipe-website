<script setup lang="ts">
import SearchMenu from './SearchMenu.vue';
import SignupMenu from './SignupMenu.vue';

</script>

<template>
    <div
      class="header__navbar row justify-content-between align-items-center"
      style="width: 450px"
    >
        <SearchMenu></SearchMenu>
        <SignupMenu></SignupMenu>
    </div>
  </template>
  