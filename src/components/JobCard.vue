<template>
<div>
    <b-col>
        <b-card
          :title="name"
          img-src="https://fastly.syfy.com/sites/syfy/files/styles/1200x680/public/wire/legacy/sga.jpg?offset-x=0"
          img-alt="Atlantisz"
          img-top
          tag="article"
          style="max-width:300px"
          class="mb-2"
          footer="Card Footer"
        >
          <b-card-text>
            Mert szeretem :D
          </b-card-text>
          <b-button variant="primary">Apply</b-button>
        </b-card>
      </b-col>
</div>
    
</template>

<script>
export default {
    props: ["name"]
}
</script>

<style scoped>

</style>