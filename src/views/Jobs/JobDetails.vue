<template>
  <h1>Job Details Page</h1>
  <p>Job ID is {{ id }}</p>
</template>

<script>
export default {
    props: ['id'],
    data() {
        return {
        //    jobId: this.$route.params.id     
        }
    }
}
</script>

<style>

</style>