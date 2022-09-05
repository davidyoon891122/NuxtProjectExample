<template>
  <div class="container">
    <NuxtLogo />
    메인
    {{ $store.state.user.email }}
  </div>
</template>

<script>
export default {
    name: "IndexPage"
}
</script>
