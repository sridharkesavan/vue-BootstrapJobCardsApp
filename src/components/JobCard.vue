<template>
    <div>
        <b-col>
        <b-card :title="name"
        img-src="https://xndev.com/wp-content/uploads/2012/03/writing_600_300.jpg"
        img-alt="Job-info"
        img-top=""
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        footer="Card Footer">
            <b-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt consequatur illum reiciendis labore cumque qui. Corrupti doloribus eum totam dolor possimus ea quae aliquid. Numquam suscipit sequi animi! Recusandae, consequatur.
            </b-card-text>
            <b-button variant="primary">Apply</b-button>
        </b-card>
        </b-col>
    </div>
</template>

<script>
    export default {
        props: ['name']
    }
</script>

<style lang="scss" scoped>

</style>