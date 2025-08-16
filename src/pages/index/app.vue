<template>
  <div class="home-page">
    <pianoBanner />
    <div class="dashang-wrapper">
      <p class="intros">
      </p>
      <dashang />
    </div>
  </div>
</template>

<script>
import pianoBanner from './comps/piano-banner.vue';
import dashang from '../../comp/xw-comp/dashang/index.vue';

export default {
  name: 'HelloWorld',
  components: {
    pianoBanner,
    dashang,
  },
  props: {
  },
};
</script>

<style lang="stylus">
.home-page {
  >.dashang-wrapper {
    margin 6em 0 3em;
    text-align center;
    >.intros {
      font-size 14px;
      margin 1em 1em;
    }
  }
}
</style>
