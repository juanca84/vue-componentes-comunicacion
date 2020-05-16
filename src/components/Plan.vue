<template>
    <div>
      <div class="plan">
        <div class="descripcion">
          <span class="titulo">{{ nombre }}</span>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: 'plan',
        props: {
            nombre: {
                type: String,
                default: 'Plan 1 - Principiante',
                required: true
            },
            precio: Number
        }
    }
</script>

<style lang="scss" scoped>

</style>