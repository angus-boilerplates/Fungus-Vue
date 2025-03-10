<script setup lang="ts">
import AppLogoIcon from '@/components/AppLogoIcon.vue';
import AppLogoText from '@/components/AppLogoText.vue';

</script>

<template>
    <div class="flex aspect-square size-8 items-center justify-center rounded-md bg-sidebar-primary text-sidebar-primary-foreground">
        <AppLogoIcon class="size-5 fill-current text-white dark:text-black" />
    </div>
    <div class="ml-1 grid flex-1 text-left text-sm">
        <AppLogoText class="h-8" />
    </div>
</template>
