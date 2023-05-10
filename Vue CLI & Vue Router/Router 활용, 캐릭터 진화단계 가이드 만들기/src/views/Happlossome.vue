<template>
  <div class="wrap">
    <h2 class="text-center">2단계</h2>
    <div class="d-flex">
        <div><button @click="no">이전</button></div>
        <div><img src="../assets/happlossome.png" alt="" class="img"></div>
        <router-link to="/happlower">다음</router-link>
    </div>
    <h2 class="text-center">해플라썸</h2>
  </div>
</template>

<script>
export default {
    methods: {
        no() {
            alert("이전 진화 단계로 돌아갈 수 없습니다.")
        },
    }
}
</script>

<style>

</style>