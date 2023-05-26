<template>
    <div>
        <h1 style="margin-top: 10rem;">{{estado}}</h1>
    </div>
</template>

<script>
export default {
    name: 'VerificacionView',
    data() {
        return {
            estado: '',
        }
    },
    beforeMount() {
        this.estado = this.$route.params.estado;
    },
}
</script>