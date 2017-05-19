<template lang="html">
  <div class="">
    <br><br>
    <div class="space">
    <div class="field">
      <label class="label">เรื่อง </label>
      <input class="input" type="text" placeholder="(Ex.ท่อน้ำปะปาแตก)"><br><br>
      <label class="label">สถานที่เกิดเหตุ</label>
      <input class="input" type="text" placeholder="(Ex.สี่แยกราชประสงค์)"><br><br>
      <button class="button is-primary font-issue">เพิ่มรูป</button><br><br>
      <div class="columns is-mobile is-multiline is-gapless">
        <div class="column box-x">
          <span class="level-center">
            <i class="fa fa-times-circle level-item" aria-hidden="true"></i>
          </span>
          <img src="https://cms.kapook.com/uploads/tag/2/ID_1842_5729d75b5be69.jpg" alt="">
        </div>
      </div>
      <label class="label">รายละเอียด</label>
      <textarea class="textarea" placeholder="รายละเอียด"></textarea><br>
      <label class="label">เบอร์โทรศัพท์</label>
      <input class="input" type="text" placeholder="xxx-xxxxxxx"><br><br>
    </div>
    <div class="field is-grouped">
      <p class="control">
        <button class="button is-primary font-issue">แจ้งเหตุ</button>
      </p>
      <p class="control">
        <button class="button is-link font-issue">ยกเลิก</button>
      </p>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  },
  computed: {},
  mounted () {},
  methods: {},
  components: {}
}
</script>

<style lang="css" scope>
.space{
  padding-left: 5px !important;
  padding-right: 5px !important;
  padding-top: 10px;
  margin-left: 5px !important;
  margin-right: 5px !important;
  margin-top: 10px ;
  background-color: white;
  height: 100%;
  padding-bottom: 100px;
  border-radius: 2px;
}
.font-issue {
  font-family: 'Kanit', sans-serif;
}
.box-x img{
  width: 98%;
}
</style>
