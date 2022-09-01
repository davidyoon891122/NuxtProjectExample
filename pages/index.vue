<template>
  <div class="container">
    메인
    {{ $store.state.user.email }}
  </div>
  <Tutorial/>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
