<template>
    <div class="container">
        {{$route.params.board}}게시판 생성하기
        <MainButton @click="movePage">이동</MainButton>
    </div>
</template>
<script>
export default {
    methods: {
        movePage() {
            this.$router.push({
                name: "board-create-board",
                params: {
                    board: "long-board-name"
                },
                query: {
                    page: 5
                }
            })
        }
    }
}
</script>
<style>

</style>