<template>
  <div class="usuario-editar">
    <h3>Usuário Editar</h3>
    <p><strong>Código: </strong>{{ id }}</p>
    <p><strong>Idade: </strong> {{ $route.query.idade }}</p>
    <p><strong>Nome: </strong> {{ $route.query.nome }}</p>
  </div>
</template>

<script>
export default {
  props: ['id'],
}
</script>

<style>

</style>