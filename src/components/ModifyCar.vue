<template>
  <div class="app">
    <el-radio v-model="radio" label="1">备选项</el-radio>
  <el-radio v-model="radio" label="2">备选项</el-radio>
  </div>
</template>

<script>
export default {
 data () {
      return {
        radio: '1'
      };
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
