<template>
  <main class="user-layout bg-gray-200">
    <article class="sidebar">
      <p>Dashboard</p>
      <p>Settings</p>
    </article>
    <section>
         <!-- here nuxt will replace with page content -->
      <slot></slot>
    </section>
  </main>
</template>
<style scoped>
.sidebar {
  display: flex;
  flex-direction: column;
}
.user-layout {
  display: flex;
}
</style>
