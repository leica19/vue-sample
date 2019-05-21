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
    <label for="">名前</label>
    <input type="text" class="form-control" placeholder="shigaki daichi" required>
  </div>
  <div class="form-group">
    <label for="">年齢</label>
    <input type="text" class="form-control" placeholder="12" required>
  </div>
   <div class="form-group">
    <input type="radio">
    <label for="">男性</label>
    <input type="radio">
    <label for="">女性</label>
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
