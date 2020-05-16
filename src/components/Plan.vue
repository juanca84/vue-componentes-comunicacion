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
        props: ['nombre']
    }
</script>

<style lang="scss" scoped>

</style>