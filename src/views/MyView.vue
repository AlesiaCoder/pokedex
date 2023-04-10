<script>
import DirectiveVShow from '../components/myComponents/directives/DirectiveVShow.vue';
import DirectiveVif from '../components/myComponents/directives/DirectiveVif.vue';
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
export default {
  components: { SingleComponent, RawHtmlData, DirectiveVShow, DirectiveVif },};
</script>

<template>
    <div>
        <h1>My Single Page from FemCoder</h1>
        <h3>Lorem ipsum dolor, sit amet consectetur...</h3>
        ----------------------------------
        <single-component></single-component>
        ----------------------------------
        <raw-html-data></raw-html-data>
        ----------------------------------
        <directive-v-show></directive-v-show>
        ----------------------------------
        <directive-vif></directive-vif>
    </div>
</template>

<style lang="css" scoped>
    h1 {
        color: pink;
    }
</style>