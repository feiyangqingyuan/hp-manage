<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'FeiyangGit',
  data() {
    return {
      url: 'https://github.com/feiyangqingyuan/hp-manage.git'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
