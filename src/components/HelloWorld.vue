<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Vue
        </a>
      </li>
      <li>
        <a
          href="https://yunyoujun.cn/note/vue-parcel-demo/"
          target="_blank"
        >
          Note
        </a>
      </li>
      <li>
        <a
          href="https://parceljs.org"
          target="_blank"
        >
          Parcel
        </a>
      </li>
      <li>
        <a
          href="https://github.com/YunYouJun"
          target="_blank"
        >
          @YunYouJun
        </a>
      </li>
      <br>
      <li>
        <a
          href="https://github.com/YunYouJun/vue-parcel-demo"
          target="_blank"
        >
          Demo
        </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="https://github.com/YunYouJun/give-me-money"
          target="_blank"
        >
          I'm cute!
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js + Parcel App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
