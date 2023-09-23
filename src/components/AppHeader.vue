<script>

export default {
  name: "AppHeader"
}
</script>

<template>
  <header>
    <div class="container py-3">
      <div class="d-flex justify-content-between align-items-center">
        <h1>Blog</h1>
        <nav>
          <ul class="list-unstyled m-0 p-0 gap-4 d-flex align-items-center">
            <li>
              <router-link :to="{ name: 'home' }" class="nav-link">
                Home
              </router-link>
            </li>
            <li>
              <router-link :to="{ name: 'about' }" class="nav-link">
                About
              </router-link>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #00AC8C;
  color: white;
}
</style>