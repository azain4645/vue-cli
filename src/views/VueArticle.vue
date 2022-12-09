<template>
  <span>記事コード：{{ aid}}</span>
</template>

<script>
export default {
  name: 'VueArticle',
  props:{
    aid: String
  }
}
</script>