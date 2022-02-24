<template>
  <div>
    <h1>{{variavel}}</h1>
    <p>Link da API: {{ url_api }}</p>
    <p>Modo: {{modo}}</p>
    <p>Token: {{token}}</p>
  </div>
</template>

<script>
export default {
  data: () => ({
      variavel: process.env.VUE_APP_VARIAVEL_DE_AMBIENTE,
      url_api: process.env.VUE_APP_API_URL,
      modo: process.env.VUE_APP_MODO,
      teste: process.env.VUE_APP_MODO,
      token: process.env.VUE_APP_TOKEN
    }),
  name: 'HelloWorld'
}
</script>

<style>

</style>
