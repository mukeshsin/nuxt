<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
        <a href="/about">normal link -- about page</a>
      </nav>
    </header>
    <h1>Home</h1>
    <p>this is my nuxt project</p>
    <p>this is my nuxt project</p>
  </div>
</template>

<script setup></script>

<style scoped>
h1{
    margin-bottom:20px;
    font-size:36px;
}
p{
    margin:20px 0;
}
</style>
