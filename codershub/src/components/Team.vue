<template>
  <div class="team">
      <h1>Our Team/{{teamId}}</h1>
  </div>
</template>

<script>
export default {
    name: "Team",
    data() {
        return{
            teamId: this.$route.params.team_id
        }
    }
}
</script>

<style>

</style>