
<script>
import InputTag from './components/InputTag.vue'

export default {

  components: {
    InputTag,
  },

  methods:{
    handleOnTagsChange(tags){
      console.log(tags)
    },
  },
};
</script>

<template>

  <InputTag @onTagsChange="handleOnTagsChange"></InputTag>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
