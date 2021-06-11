<template>
  <h1>Programming</h1>
  <p>今までの成果物です</p>
  <div class="portfolio pf-1">
    <table>
      <td class="left"><img src="../assets/Kanban.png" /></td>
      <td class="right">
        <ul>
          <li>■Torello風アプリ</li>
          <li>created : 2020.8</li>
          <li>framework : Ruby on Rails</li>
          <li>
            <a
              class="pf-link"
              href="https://fast-beyond-94911.herokuapp.com/users/sign_in"
              >Link</a
            >/<a class="pf-link" href="https://github.com/yunari26/kanban"
              >GitHub</a
            >
          </li>
          <li>
            Comment : Rails<span>の勉強をしたくて試しに作りました。</span>
          </li>
        </ul>
      </td>
    </table>
  </div>

  <div class="portfolio pf-2">
    <table>
      <td class="left"><img src="../assets/LaravelBookReview.png" /></td>
      <td class="right">
        <ul>
          <li>■ブックレビューサイト</li>
          <li>created : 2021.5</li>
          <li>framework : Laravel8</li>
          <li>
            <a class="pf-link" href="http://laravel-book-review.online/">Link</a
            >/<a
              class="pf-link"
              href="https://github.com/yunari26/laravel-book-review"
              >GitHub</a
            >
          </li>
          <li>
            Comment : AWS<span
              >環境での開発・デプロイ、独自ドメイン取得の練習。</span
            >
          </li>
        </ul>
      </td>
    </table>
  </div>
</template>

<style scoped>
h2 {
  font-size: 20px;
}
.portfolio {
  padding-top: 30px;
  vertical-align: middle;
}
table {
  width: 100%;
  margin: 0 auto;
}
td {
  text-align: center;
  vertical-align: middle;
}
.left {
  width: 50%;
}
.right {
  text-align: left;
  width: 50%;
}
li {
  font-size: 18px;
  list-style: none;
}
li a {
  font-size: 18px;
}
span {
  font-size: 70%;
}
</style>
