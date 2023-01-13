<template>
  <div class="wrap">
    <div>ヘッダー</div>
    <main class="main">メイン</main>
    <div>フッター</div>
  </div>
</template>

<style>
@import 'assets/css/destyle.css'; 

.wrap {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  width: 370ph;
  margin: 0 auto;
  font-family: sans-serif;
}

.main {
  flex: 1;
  width: 100%;
}
</style>
