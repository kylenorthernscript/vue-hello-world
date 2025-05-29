<template>
  <div id="app">
    <h1>{{ message }}</h1>
    <div class="description">
      <h2>このプログラムについて：</h2>
      <p>{{ description.purpose }}</p>
      <p>{{ description.technology }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World',
      description: {
        purpose: 'Vue.js 3を使用したシンプルなWebアプリケーションです。',
        technology: 'Viteをビルドツールとして使用し、効率的な開発環境を提供します。'
      }
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  font-size: 2.5em;
  margin: 0.67em 0;
}

.description {
  margin-top: 40px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

h2 {
  font-size: 1.5em;
  color: #42b883;
  margin-bottom: 20px;
}

p {
  font-size: 1.1em;
  line-height: 1.6;
  margin: 10px 0;
  color: #666;
}
</style>