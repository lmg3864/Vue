<template>
  <div class="wrap">
    <h2 class="text-center">시작</h2>
    <div class="d-flex">
      <div><button @click="no">이전</button></div>
      <div><img src="../assets/happeed.png" alt="" class="img"></div>
      <router-link to="/happling">다음</router-link>
    </div>
    <h2 class="text-center">해피드</h2>
  </div>
</template>

<script>
export default {
  name: 'happeed',
  methods: {
    no() {
            alert("이전 진화 단계로 돌아갈 수 없습니다.")
        },
  }
}
</script>

<style>
.img{
    width: 200px;
}
.d-flex {
    display: flex;
}
.wrap {
  border: 1px solid gray;
}
</style>