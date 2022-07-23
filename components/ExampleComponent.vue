<template>
  <div>
    <h1>Это компонент - ребенок</h1>
    <p>Сюда мы хотим передать переменную <b>{{ var_comp }}</b></p>
  </div>
</template>

<script>
export default {
  props: ['var_comp']
}
</script>

<style>

</style>
