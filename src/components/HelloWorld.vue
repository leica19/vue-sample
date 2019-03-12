<template>
  <div class="hello">
    <h1>ユーザーの一覧</h1>

    <ul class="nav">
      <li class="nav-item">
        <router-link to="/create">新規登録</router-link>
      </li>
    </ul>

    <ul class="list-group">
      <li class="list-group-item">さる</li>
      <li class="list-group-item">きつね</li>
      <li class="list-group-item">たぬき</li>
    </ul>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
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
