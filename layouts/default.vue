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
  color: white;
}
.title-color{
    color: #FFCB31;
}

.main-color{
color: #1A8c97;
}

.con-color{color: #242943;
}

.main-content{
  margin-top: 4.5rem;

}


</style>
