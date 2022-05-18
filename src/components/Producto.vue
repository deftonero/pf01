<template></template>

<script>
export default {
  name: "Producto",
  data() {
    return {
      producto: {
        nombre: "",
        precio: "",
        descripcion: "",
        imagen: "",
        categoria: "",
      },
      categorias: [],
      errors: [],
    };
  },
};
</script>

<style></style>
