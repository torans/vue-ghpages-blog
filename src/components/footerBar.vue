<template>
  <footer class="footer">
    Copyright © {{ thisYear }} | Powered by <a href="https://shetu.cc" target="_blank">shetu.cc</a>
  </footer>
</template>

<script>
  export default {
    data () {
      return {
        thisYear: new Date().getFullYear()
      }
    }
  }
</script>
