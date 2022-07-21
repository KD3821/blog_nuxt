<template>
  <div>
    <ExampleComponent2 @sendTopage="data_from_component = $event"/>
    <h1>Это страница - родитель</h1>
    <p>Это данные из компонента <b>{{ data_from_component }}</b></p>
  </div>
</template>

<script>
import ExampleComponent2 from "../components/ExampleComponent2";
export default {
  components: {
    ExampleComponent2
  },
  data() {
    return {
      data_from_component: ""
    }
  }
}
</script>

<style>

</style>
