<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>ICT Smart Controll Devices</h2>
    <ul>
      <li>
        <a
          href="https://#"
          target="_blank"
        >
          ๐ฎ์ถ์ฌํ๊ฒฝ์ ์ด๊ธฐ
        </a>
      </li>
      <li>
        <a
          href="https://#"
          target="_blank"
        >
         ๐ท๋์ฌํ๊ฒฝ์ ์ด๊ธฐ
        </a>
      </li>
      <li>
        <a
          href="https://#"
          target="_blank"
        >
          ๐์๊ณํ๊ฒฝ์ ์ด๊ธฐ
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/goodkn"
          target="_blank"
        >
          ๐๏ธ๋์ํํ๊ฒฝ์ ์ด๊ธฐ
        </a>
      </li>
      <br>
    </ul>
    <h2>๋ฐ๋์ฒด์ฅ๋น ์ ๋ฌธ์ ์กฐ ์์ฒด</h2>
    <ul>
      <li>
        <a
          href="http://#/"
          target="_blank"
        >
         Semiconductor Rrobot-lift
        </a>
      </li>
      <li>
        <a
          href="http://#/"
          target="_blank"
        >
          PCB & Artwork
        </a>
      </li>
      <li>
        <a
          href="http://#/"
          target="_blank"
        >
          Ventilation System
        </a>
      </li>
      <li>
        <a
          href="https://#"
          target="_blank"
        >
         Electronic dev device
        </a>
      </li>
    </ul>
    <ul>
      <li><button v-on:click="Controller">Controller</button></li>
      <li><b-button variant="primary">Sensor</b-button></li>
    </ul>
<br>
<ul>
<li><span>GOODKN.company Copyallrights2023 reserved</span></li>
</ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to GOODKNelectro Company'
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
span {
  font-size: 2.2pt
}
</style>
