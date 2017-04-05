<template>
    <div class="index-right">
      <slide-show :slides="slides" :inv="invTime"></slide-show>
    </div>
</template>

<script>
import slideShow from '../components/slideShow'
export default {
  components: {
    slideShow
  },
  data () {
    return {
      invTime: 2000,
      slides: [
        {
          src: require('../url.jpg'),
          title: '1',
          href: 'http://xxx.xxx.com'
        },
        {
          src: require('../url.jpg'),
          title: '2',
          href: 'http://xxx.xxx.com'
        },
        {
          src: require('../url.jpg'),
          title: '3',
          href: 'http://xxx.xxx.com'
        },
        {
          src: require('../url.jpg'),
          title: 'x4',
          href: 'http://xxx.xxx.com'
        }
      ],
      }
    }
  }
</script>

<style scoped>
..
</style>
