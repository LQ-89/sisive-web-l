<template>
  <div class="list">
    <router-link to="/home">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("home")}}
      </span>
    </router-link>
    <router-link to="/about">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("aboutus")}}
      </span>
    </router-link>
    <router-link to="/moreAdvisers">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("view")}}
      </span>
    </router-link>
    <router-link to="/moreServices">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("media")}}
      </span>
    </router-link>
    <router-link to="/moreStudents">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("history")}}
      </span>
    </router-link>
    <router-link to="/moreStudents">
      <span
        class="plate"
        :style="{color: color}"
      >{{$t("contactus")}}
      </span>
    </router-link>
    <span class="plate" @click="_changeLanguage" :style="{color: color}">{{$t("message.language")}}</span>
  </div>
</template>
<script type="text/ecmascript-6">
export default {
  props: {
    color: {
      type: String,
      default: ''
    }
  },
  methods: {
    _changeLanguage() {
      this.$i18n.locale = this.$i18n.locale === 'en' ? 'zh_CN' : 'en'
      window.localStorage.setItem('immi_language', JSON.stringify(this.$i18n.locale))
      window.location.reload()
    }
  }
}
</script>
<style lang="stylus" scoped rel="stylesheet/stylus">
@import '~common/stylus/variable'
@import '~common/stylus/base'
.list
  @extend .flex
  @extend .flex-row
  @extend .flex-between
  width: 100%;
  .plate
    @extend .pointer
    font-size: 14px
    color: #000000
a.router-link-active
  span
    color: #193A80 !important
    padding-bottom: 5px
    border-bottom: 1px solid #193A80 !important
</style>
