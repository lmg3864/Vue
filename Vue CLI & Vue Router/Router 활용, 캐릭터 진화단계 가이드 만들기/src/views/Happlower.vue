<template>
  <div class="wrap">
    <h2 class="text-center">3단계</h2>
    <div class="d-flex">
        <div><button @click="no">이전</button></div>
        <div><img src="../assets/happlower.png" alt="" class="img"></div>
        <div><button @click="home">다음</button></div>
    </div>
    <h2 class="text-center">해플라워</h2>
  </div>
</template>

<script>
export default {
    methods: {
        no() {
            alert("이전 진화 단계로 돌아갈 수 없습니다.")
        },
        home() {
            alert("Home으로 돌아갑니다!")
        }
    }
}
</script>

<style>

</style>