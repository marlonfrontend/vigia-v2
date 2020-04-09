<template>
  <header class="py-3">
    <div class="container mx-auto">
      <div class="flex flex-wrap">
        <div class="logo">
          <img src="@/assets/images/logo.svg" alt="">
        </div>
        <div class="search">
          <form action="#">
            <input
              type="text"
              placeholder="Buscar produtos, cupons e muito mais"
              class="p-2 rounded-l-md"
            >
            <button type="submit">Buscar</button>
          </form>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style lang="scss">
  header {
    background-color: #0e1861;
  }
</style>
