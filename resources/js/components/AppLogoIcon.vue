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

    <svg :class="className" v-bind="$attrs" width="100%" height="100%" viewBox="0 0 713 713" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;">
        <g transform="matrix(1,0,0,1,-630,-4390)">
            <g id="Artboard4" transform="matrix(1,0,0,1,-48,1187.09)">
                <rect x="678" y="3202.91" width="713" height="713" style="fill:none;"/>
                <clipPath id="_clip1">
                    <rect x="678" y="3202.91" width="713" height="713"/>
                </clipPath>
                <g clip-path="url(#_clip1)">
                    <g transform="matrix(1.11232,0,0,1.11232,-141.783,-425.493)">
                        <path d="M1378,3422.25L1378,3742.75C1378,3831.19 1306.19,3903 1217.75,3903L897.25,3903C808.806,3903 737,3831.19 737,3742.75L737,3422.25C737,3333.81 808.806,3262 897.25,3262L1217.75,3262C1306.19,3262 1378,3333.81 1378,3422.25Z" style="fill:rgb(204,52,76);"/>
                    </g>
                    <g id="mushroom" transform="matrix(22.342,0,0,22.342,766.395,3291.3)">
                        <path d="M12,2C17.523,2 22,6.477 22,12C22,13.105 21.105,14 20,14L4,14C2.895,14 2,13.105 2,12C2,6.477 6.477,2 12,2ZM12,8C13.105,8 14,7.105 14,6C14,4.895 13.105,4 12,4C10.895,4 10,4.895 10,6C10,7.105 10.895,8 12,8ZM17,12C18.105,12 19,11.105 19,10C19,8.895 18.105,8 17,8C15.895,8 15,8.895 15,10C15,11.105 15.895,12 17,12ZM7,12C8.105,12 9,11.105 9,10C9,8.895 8.105,8 7,8C5.895,8 5,8.895 5,10C5,11.105 5.895,12 7,12ZM15,15L16.27,19.45L16.347,19.997C16.349,21.102 15.455,21.998 14.35,22L9.65,22C8.545,21.998 7.651,21.102 7.653,19.997L7.73,19.45L9,15L15,15Z" style="fill:white;fill-rule:nonzero;"/>
                    </g>
                </g>
            </g>
        </g>
    </svg>

</template>
