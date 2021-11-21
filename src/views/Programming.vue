<template>
  <h1>Programming</h1>
  <p>今までの成果物です</p>
  <div class="portfolio pf-1">
    <table>
      <td class="left"><img src="../assets/ImokempiEmail.png" /></td>
      <td class="right">
        <ul>
          <li>■髪に芋けんぴがついているのを知らせるサービス</li>
          <li>framework : Ruby on Rails</li>
          <li>
            <a class="pf-link" href="https://imokenpi-email.herokuapp.com/"
              >Link</a
            >/<a
              class="pf-link"
              href="https://github.com/yunari26/imokenpi-email"
              >GitHub</a
            >
          </li>
          <li>
            Comment :
            <span>
              知り合いの髪に芋けんぴがついていても、取る勇気が出ない時、ありますよね。そんな時に使えるメール通知サービスです。
            </span>
          </li>
        </ul>
      </td>
    </table>
  </div>

  <div class="portfolio pf-2">
    <table>
      <td class="left"><img src="../assets/Kanban.png" /></td>
      <td class="right">
        <ul>
          <li>■Torello風アプリ</li>
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

  <div class="portfolio pf-3">
    <table>
      <td class="left"><img src="../assets/LaravelBookReview.png" /></td>
      <td class="right">
        <ul>
          <li>■ブックレビューサイト</li>
          <li>framework : Laravel8</li>
          <li>
            <a class="pf-link" href="#">Link</a>/<a
              class="pf-link"
              href="https://github.com/yunari26/laravel-book-review"
              >GitHub</a
            >
          </li>
          <li>
            Comment : AWS<span
              >環境での開発・デプロイ、独自ドメイン取得の練習。※現在リンク切れです。</span
            >
          </li>
        </ul>
      </td>
    </table>
  </div>

  <div class="portfolio pf-4">
    <table>
      <td class="left"><img src="../assets/Naristagram.png" /></td>
      <td class="right">
        <ul>
          <li>■Instagramクローン</li>
          <li>framework : Ruby on Rails</li>
          <li>
            <a class="pf-link" href="https://naristagram.herokuapp.com/">Link</a
            >/<a class="pf-link" href="https://github.com/yunari26/naristagram"
              >GitHub</a
            >
          </li>
          <li>
            Comment :
            <span
              >現在開発中。ログイン認証・投稿など最低限の機能しかつけていないのでこれからもっと色々追加していきたいです。</span
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
