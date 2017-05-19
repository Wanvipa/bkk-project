<template lang="html">
  <nav class="nav has-shadow colornav">
    <div class="nav-left" v-show="$route.name === 'Report'">
      <router-link :to="{path: '/'}" class="nav-item level" style="color: white;">
        <span class="level-item">
          <i class="fa fa-chevron-left" aria-hidden="true"></i>
        </span>
      </router-link>
    </div>
    <div class="nav-center" v-show="$route.name === 'Feeds'">
      <a class="nav-item" style="color: white;">
        <span>
          ปัญหา
        </span>
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {}
  },
  computed: {},
  mounted () {},
  methods: {
  },
  components: {}
}
</script>

<style lang="css">
</style>
