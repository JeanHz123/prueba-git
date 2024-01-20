<template>
  <!-- Código HTML del componente -->
  <div>
    <h1>{{ mensaje }}</h1>
    <button @click="cambiarMensaje">Cambiar Mensaje</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensaje: "¡Hola, mundo!"
    };
  },
  methods: {
    cambiarMensaje() {
      this.mensaje = "Nuevo mensaje";
    }
  }
};
</script>

<style scoped>
/* Estilos CSS específicos del componente */
h1 {
  color: green;
}
</style>
