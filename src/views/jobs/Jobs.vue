<template>
<h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{ job.title }}</h2>
  </div>
</template>

<script>
export default {
  name: "Jobs",
  data(){
    return {
      jobs: [
        { title: 'Ninja UX Designer', id: 1, details: 'lorem'},
        { title: 'Ninja web Designer', id: 2, details: 'lorem'},
        { title: 'Ninja vue Designer', id: 3, details: 'lorem'}
      ]
    }
  }
}
</script>

<style scoped>

</style>
