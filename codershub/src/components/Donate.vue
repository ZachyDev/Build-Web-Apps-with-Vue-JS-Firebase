<template>
    <div>
      <div class="jumbotron">
      <h1 class="text-primarry">Donate and support us</h1>
     </div>
     <button class="btn btn-primary" @click="goPrev">Go Back</button>
</div>

  
</template>

<script>
export default {
    name: "Donate",
    data() {
        return{}
    },
    methods: {
        goPrev() {
            this.$router.go(-1)
        }
    }
}
</script>

<style>

</style>