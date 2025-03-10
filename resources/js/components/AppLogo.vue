<script setup lang="ts">
import AppLogoDark from '@/components/ui/logo/AppLogoDark.vue';
import AppLogoLight from '@/components/ui/logo/AppLogoLight.vue';
import type { HTMLAttributes } from 'vue';

defineOptions({
    inheritAttrs: false,
});

interface Props {
    className?: HTMLAttributes['class'];
}

defineProps<Props>();

</script>

<template>
    <AppLogoDark :class="className" v-bind="$attrs" class="hidden dark:block" />
    <AppLogoLight :class="className" v-bind="$attrs" class="dark:hidden" />
</template>
