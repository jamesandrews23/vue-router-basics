<template>
<h1>Job Details Page</h1>
  <p>the job id is {{ id }}</p>
</template>

<script>
export default {
  name: "JobDetails",
  data(){
    return {
      id: this.$route.params.id
    }
  }
}
</script>

<style scoped>

</style>
