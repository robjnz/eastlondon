<template>
  <div>
    <TheHeader />
    <main class="main-content">
    <nuxt/>
    </main>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader/TheHeader'

export default {
  components: {
    TheHeader
  }
}
</script>

<style>
*{
box-sizing: border-box;
}

body {
  font-family: "lato", sans-serif;
  background : #242943;

}
.main-content{
  margin-top: 4.5rem;

}

</style>
