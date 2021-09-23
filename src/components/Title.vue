<template>
  <div class="title">
      <h1>{{ msg }}<em>{{ mainMsg }}</em></h1>
  </div>
</template>

<script>
export default {
    name: 'Title',
    props: {
        msg: String,
        mainMsg: String
    }
}
</script>

<style scoped>
    h1{
        font-size: 4em;
        color: #35495e;
    }
    em {
        color: #41b883;
    }
</style>