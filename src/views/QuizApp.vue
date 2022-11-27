<template>
  <h1>Vue クイズ</h1>
  <div class="app">
    <h2>Q. {{ "昨年ワールドカップで優勝した国はどこでしょう？" }}</h2>
    <img
      class="quiz-image"
      src="https://via.placeholder.com/300x300"
      alt="クイズタイトル"
    />
    <div class="container">
      <button>
        {{ "フランス" }}
      </button>
      <button>
        {{ "ドイツ" }}
      </button>
      <button>
        {{ "ブラジル" }}
      </button>
    </div>
    <div>{{ "フランス" }}</div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.app {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.quiz-image {
  height: 300px;
  width: 300px;
  object-fit: contain;
}

.container {
  display: flex;
  height: 2em;
  width: 300px;
  padding: 1em;
  justify-content: space-around;
}
</style>
