<template>
  <img :src="dataUri" :alt="'avatar: ' + value">
</template>

<script>
import avatar from '@voken/avatar'

export default {
  name: 'VueAvatar',
  props: {
    value: String,
  },
  computed: {
    dataUri() {
      return avatar.svgDataUriFromSeed(this.value)
    }
  }
}
</script>
