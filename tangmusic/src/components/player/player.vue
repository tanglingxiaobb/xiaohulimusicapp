<template>
    <div class="player" v-show="playlist.length>0">
      <transition name="normal" @enter="enter" @after-enter="afterEnter" @leave="leave" @after-leave="afterLeave">
        <div class="normal-player">

        </div>
      </transition>
    </div>
</template>

<script type="text/ecmascript-6]">
    export default {
    }
</script>

<style scoped>

</style>
