<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <h2>Vue.jsのテスト</h2>
    <p>適当に色々触ってみる</p>
    <test msg="test_msg"></test>
    <test/>

    <li>
      <label><input type="checkbox">label1</label>
    </li>
    <li>
      <label><input type="checkbox">label2</label>
    </li>

    <HelloWorld/>
  </div>
</template>

<script>
// コンポーネントのインポート等？
import HelloWorld from "./components/HelloWorld";
import test from "./components/test";

export default {
  name: "App",
  components: {
    HelloWorld,
    test
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
