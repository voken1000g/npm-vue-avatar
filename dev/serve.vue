<template>
  <div id="app" style="background-color: bisque; padding: 100px">
    <div style="width: 64px; height: 64px; background-color: white">
      <vue-avatar value="sample"/>
    </div>
  </div>
</template>

<script>
import Vue from 'vue';
import VueAvatar from '@/vue-avatar.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueAvatar
  }
});
</script>

