<template>
  <div class="form">

    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <router-link to="/">ユーザーの一覧</router-link>
      </ol>
    </nav>

    <h1>ユーザーの新規登録</h1>

  <form>
  <div class="form-group">
    <label for="exampleInputEmail1">名前</label>
    <input type="email" class="form-control" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">性別</label>
    <input type="password" class="form-control">
  </div>
  <button type="submit" class="btn btn-primary">登録</button>
</form>

</div>
</template>

<script>
export default {
  name: 'Form'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
