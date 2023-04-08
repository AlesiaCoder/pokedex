<script>
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
export default {
  components: { SingleComponent, RawHtmlData },};
</script>

<template>
<div>
    <h3>My Single Page</h3>
    <single-component></single-component>
    <single-component></single-component>
    <single-component></single-component>
    <single-component></single-component>
    <raw-html-data></raw-html-data>

</div>
</template>

<style lang="css" scoped>
    h1 {
        color: pink;
    }
</style>