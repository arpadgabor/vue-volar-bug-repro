<script setup lang="ts">
import { RouterView } from 'vue-router';

import { Accordion } from 'ui/ui/accordion';
</script>

<template>
  <header>
    <div>
      <Accordion></Accordion>
    </div>
  </header>

  <RouterView />
</template>
