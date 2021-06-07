<template>
  <nav>
    <ul>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/jsp">Plus tard</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<script>

  export default {}

</script>

<style scoped>
  nav {
    padding: 0 1rem;
  }

  nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
  }

  nav ul li {
    padding: 1rem;
    font-size: 1.2rem;
  }
</style>
