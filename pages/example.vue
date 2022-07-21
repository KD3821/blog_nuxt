<template>
  <div>
    <ExampleComponent :variable="variable" />
    <h1>Это страница-родитель</h1>
  </div>
</template>

<script>
import ExampleComponent from "../components/ExampleComponent"
export default {
  components: {ExampleComponent},
  data() {
    return {
      variable: "[Я из родителя]"
    }
  }

}
</script>

<style>

</style>
