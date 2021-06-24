<template>
  <b-button class="b-btn-apply" squared variant="primary" @click="scroll()"> INTERESTED? <b>APPLY NOW</b> </b-button>
</template>

<script>
export default {
    methods: {
        scroll() {
            document.querySelector(this.href).scrollIntoView({behaviour: 'smooth'});
        }
    },
    props: ['href'],
}
</script>

<style>

</style>