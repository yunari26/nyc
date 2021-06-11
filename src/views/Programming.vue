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
</template>

<style scoped>
h2 {
  font-size: 20px;
}
.portfolio {
  padding-top: 30px;
}
table {
  margin: 0 auto;
}
td {
  text-align: center;
  vertical-align: middle;
}
.left {
  width: 400px;
}
.right {
  text-align: left;
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
