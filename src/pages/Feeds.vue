<template lang="html">
  <div class="">
    <card-issues :show-comment="showComment"></card-issues>
    <comments :modal-style="modalStyle" :show-comment="showComment"></comments>
  </div>
</template>

<script>
import CardIssues from '../components/CardIssues'
import Comments from '../components/Comments'
export default {
  data () {
    return {
      modalStyle: 'modal'
    }
  },
  components: {
    CardIssues,
    Comments
  },
  methods: {
    showComment () {
      if (this.modalStyle === 'modal') {
        this.modalStyle = 'modal is-active'
      } else {
        this.modalStyle = 'modal'
      }
    }
  }
}
</script>

<style lang="css">
</style>
