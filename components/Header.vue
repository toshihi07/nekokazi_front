<template >
  <header class="header">
      <router-link to="/"><img src="http://nekokaji.com/wp-content/uploads/2018/12/nekokaji-logo.png" alt=""></router-link>
    <nav class="pc-nav">
      <ul class="header_left">
          <li class="header_link"><a href="/">ホーム</a></li>
          <li class="header_link"><a href="/schedule">スケジュール</a></li>
          <li class="header_link"><a href="/cash-game">仮想CashGameFestival</a></li>
          <li class="header_link"><a href="/payment-system">料金システム</a></li>
          <li class="header_link"><a href="/access">アクセス</a></li>
          <li class="header_link"><a href="/introduction">お店の紹介</a></li>
          <li class="header_link"><a href="/adoption">採用情報</a></li>
        </ul>
    </nav>  
</header>
</template>

<script>
export default {
  name: "Footer",
  props: {
    title: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="css" scoped>
.header {
    margin: 0 auto;
    padding: 20px;
    padding: 20p;
    display: flex;
    justify-content: flex-start;
    margin: 0 auto;
    max-width: calc(100% - 20px);
}

.header .header_left{
    display: flex;
    list-style: none;
    padding-left: 0;
}

.header .header_link{
  padding: 20px 10px;
  text-decoration: none;;
}
</style>