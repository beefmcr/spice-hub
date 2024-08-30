<template>
  <div class="flex items-center justify-between px-4 h-14">
    <div class="flex items-center gap-x-4">
      <h2 class="text-xl md:text-2xl text-primary font-bold">Spicy Chat</h2>
    </div>
  </div>
</template>

<script setup lang="ts">
defineEmits(['clear', 'showDrawer']);

defineProps({
  clearDisabled: {
    type: Boolean,
    default: true,
  },
});
</script>
