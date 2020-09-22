<template>
  <div class="team">
      <div class="jumbotron">
           <h1>Our Team/{{teamId}}</h1>
      </div>
      <button class="btn btn-primary" @click="goPrev">Go Back</button>
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
        }, 
        goPrev() {
           this.$router.go(-1)
        }
    },
    watch: {
        $route: "updateId"
    }
}
</script>

<style>

</style>