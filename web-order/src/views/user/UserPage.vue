<template>
  <div class="container">
    <div class="comp-header">
      <comp-header />
    </div>
    <div class="comp-body">
      <router-view v-slot="{ Component }">
        <transition name="component-transition" mode="out-in">
          <component :is="Component" />
        </transition>
      </router-view>
    </div>
    <!-- <div class="nav-under">
      <nav-under />
    </div> -->
  </div>
</template>

<script>
// import NavUnder from '../../components/NavUnder.vue'
import CompHeader from './components/CompHeader.vue';

export default {
  components: {
    // NavUnder,
    CompHeader,
  },
};
</script>

<style lang="scss" scoped>
.comp-header {
  display: block;
  height: 43.2px;
  z-index: 100;
}

.comp-body {
  padding-bottom: 12vh;
  overflow-x: hidden;
}

@media screen and (max-height: 799px) {
    .comp-body {
      padding-bottom: 14vh;
    }
}

.component-transition-enter-active,
.component-transition-leave-active {
  transition-duration: 0.2s;
  transition-property: opacity;
  transition-timing-function: ease;
}

.component-transition-enter,
.component-transition-leave-active {
  opacity: 0
}

</style>
