<template>
  <div>
    <nav-bar></nav-bar>

    <section class="main-content">
      <nuxt/>
    </section>
  </div>
</template>

<script>
  import NavBar from '~/components/NavBar';

  export default {
    components: {
      NavBar,
    },

    head: {
      bodyAttrs: {
        class: 'has-navbar-fixed-top',
      },
    },
  };
</script>
