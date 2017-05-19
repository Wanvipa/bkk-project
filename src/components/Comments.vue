<template lang="html">
  <div :class="modalStyle">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Comment</p>
        <button class="delete" @click="showComment"></button>
      </header>
      <div class="modal-card-body comment">
        <div class="card">
          <div class="card-content">
            <div class="media">
              <div class="media-left">
                <figure class="image is-48x48">
                  <img src="http://bulma.io/images/placeholders/96x96.png" alt="Image">
                </figure>
              </div>
              <div class="media-content">
                <p class="title is-5">John Smith</p>
                <p class="subtitle is-6">ใช่ๆ เราก็เจอเหมือนกัน อยากให้แก้เร็วๆ</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <footer class="modal-card-foot level">
        <input class="input" type="text" placeholder="Text input">&nbsp;
        <span><a class="button">Button</a></span>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  props: ['modalStyle', 'showComment'],
  data () {
    return {}
  },
  computed: {
  },
  mounted () {},
  methods: {},
  components: {}
}
</script>

<style lang="css">
.comment {
  height: 100vh;
  padding: 0px !important;
}
</style>
