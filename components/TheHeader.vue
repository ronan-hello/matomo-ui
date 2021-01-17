<template>
  <header>

    <NuxtLink to="/" class="navbar-brand">
      <Logo/>
    </NuxtLink>

  </header>
</template>

<script>
import Logo from './Logo';

export default {

  components: {Logo}

}
</script>
