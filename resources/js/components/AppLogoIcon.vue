<script setup lang="ts">
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

    <svg :class="className" v-bind="$attrs" width="100%" height="100%" viewBox="0 0 477 477" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;">
        <g id="Artboard2" transform="matrix(1,0,0,1,0,-953)">
            <rect x="0" y="953" width="477" height="477" style="fill:none;"/>
            <g id="mushroom" transform="matrix(23.85,0,0,23.85,-47.7,905.3)">
                <path d="M12,2C17.523,2 22,6.477 22,12C22,13.105 21.105,14 20,14L4,14C2.895,14 2,13.105 2,12C2,6.477 6.477,2 12,2ZM12,8C13.105,8 14,7.105 14,6C14,4.895 13.105,4 12,4C10.895,4 10,4.895 10,6C10,7.105 10.895,8 12,8ZM17,12C18.105,12 19,11.105 19,10C19,8.895 18.105,8 17,8C15.895,8 15,8.895 15,10C15,11.105 15.895,12 17,12ZM7,12C8.105,12 9,11.105 9,10C9,8.895 8.105,8 7,8C5.895,8 5,8.895 5,10C5,11.105 5.895,12 7,12ZM15,15L16.27,19.45L16.347,19.997C16.349,21.102 15.455,21.998 14.35,22L9.65,22C8.545,21.998 7.651,21.102 7.653,19.997L7.73,19.45L9,15L15,15Z" style="fill-rule:nonzero;"/>
            </g>
        </g>
    </svg>

</template>
