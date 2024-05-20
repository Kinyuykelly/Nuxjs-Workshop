<template>
  <div>
   <nav> 
   <NuxtLink to="/">Home</NuxtLink>
   <NuxtLink to="about">About</NuxtLink>
   <NuxtLink to="profile">Profile</NuxtLink>
</nav>
   <!-- here nuxt will replace with page content -->
   <slot></slot>
  </div>
</template> 