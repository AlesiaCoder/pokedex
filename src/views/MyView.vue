<script>
import ComputedProps from '../components/myComponents/computed-properties/ComputedProps.vue'
import DirectiveVFor from '../components/myComponents/directives/DirectiveVFor.vue';
import DirectiveVModel from '../components/myComponents/directives/DirectiveVModel.vue';
import DirectiveVIf from '../components/myComponents/directives/DirectiveVIf.vue';
import DirectiveVShow from '../components/myComponents/directives/DirectiveVShow.vue';
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
export default {
  components: { SingleComponent, RawHtmlData, DirectiveVShow, DirectiveVIf, DirectiveVModel, DirectiveVFor, ComputedProps },};
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
        <directive-v-if></directive-v-if>
        ----------------------------------
        <directive-v-model></directive-v-model>
        ----------------------------------
        <directive-v-for></directive-v-for>
        ----------------------------------
        <computed-props></computed-props>
    </div>
</template>

<style lang="css" scoped>
    h1 {
        color: pink;
    }
</style>