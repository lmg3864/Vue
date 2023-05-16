<template>
  <div>
    <h5>{{ article.title }}</h5>
    <p>{{ article.content }}</p>
    <hr>
    <p>{{article.created_at}}</p>
    <!-- <router-link :to="{
      name: 'DetailView',
      params: {id: article.id }}">
      [DETAIL]
    </router-link> -->
    <hr>
  </div>
</template>

<script>
export default {
  name: 'ArticleListItem',
  props: {
    article: Object,
  }
}
</script>

<style>

</style>
