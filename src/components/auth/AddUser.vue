<template>
  <div id="app" class="absolute   ">
    <Popover :goTo="'User'" />
  </div>
</template>

<script>
import Popover from "@/components/popover/PopoverLayout.vue";
export default {
  components: {
    Popover,
  },
};
</script>
