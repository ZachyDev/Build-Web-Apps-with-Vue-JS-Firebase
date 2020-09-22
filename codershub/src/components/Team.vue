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
    },
    methods: {
        updateId() {
            this.teamId = this.$route.params.team_id
        }
    },
    watch: {
        $route: "updateId"
    }
}
</script>

<style>

</style>