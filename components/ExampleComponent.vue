<template>
  <div>
    <h1>Это компонент - ребенок</h1>
    <p>Сюда мы хотим передать переменную <b>{{ variable }}</b></p>
  </div>
</template>

<script>
export default {
  props: ['variable']
}
</script>

<style>

</style>
