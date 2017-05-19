<template lang="html">
  <nav class="nav has-shadow button-issue">
    <div class="nav-center" v-show="$route.name === 'Feeds'">
      <router-link class="nav-item" style="color: white;" :to="{ path: 'report' }">
        <span>
          <i class="fa fa-plus-circle" aria-hidden="true"></i>&nbsp;
          รายงานปัญหา
        </span>
      </router-link>
    </div>
  </nav>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
