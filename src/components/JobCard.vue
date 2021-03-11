<template>
<div>
    <b-col>
        <b-card
          :title="name"
          img-src="https://i.pinimg.com/736x/6c/4e/48/6c4e483fe6a60c70691015656d74caa6.jpg"
          img-alt="bácsi"
          img-top
          tag="article"
          style="max-width:300px"
          class="mb-2"
          footer="Card Footer"
        >
          <b-card-text>
            Egy ajtó csapkodást megérne a Bácsi :D
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