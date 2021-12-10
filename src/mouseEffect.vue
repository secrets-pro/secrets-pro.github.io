<template>
     <canvas class="fireworks"
        style="position: fixed; left: 0; top: 0; z-index: 99999999; pointer-events: none;"></canvas>
</template>
<script>
import init from './mouseEffect';
export default {
    mounted(){
        init();
    }
}
</script>