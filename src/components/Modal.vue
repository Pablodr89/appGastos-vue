<script setup>

</script>

<template>
    <div>

    </div>
</template>

<style scoped>
    .modal {
        position: absolute;
        background-color: rgb(0 0 0 / 0.9);
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
    }
    .cerrar-modal {
        position: absolute;
        right: 3rem;
        top: 3rem;
    }
    .cerrar-modal img {
        width: 3rem;
        cursor: pointer;
    }

    .contenedor-formulario {
        transition-property: all;
        transition-duration: 300ms;
        transition-timing-function: ease-in;
        opacity: 0;
    }
    .contenedor-formulario.animar {
        opacity: 1;
    }

    .contenedor-formulario.cerrar {
        opacity: 0;
    }

    .nuevo-gasto {
        margin: 10rem auto 0 auto;
        display: grid;
        gap: 2rem;
    }
    .nuevo-gasto legend {
        text-align: center;
        color: var(--blanco);
        font-size: 3rem;
        font-weight: 700;
    }
    .campo {
        display: grid;
        gap: 2rem;
    }
    .nuevo-gasto input,
    .nuevo-gasto select {
        background-color: var(--gris-claro);
        border-radius: 1rem;
        padding: 1rem;
        border: none;
        font-size: 2.2rem;
    }
    .nuevo-gasto label {
        color: var(--blanco);
        font-size: 3rem;
    }
    .nuevo-gasto input[type="submit"] {
        background-color: var(--azul);
        color: var(--blanco);
        font-weight: 700;
        cursor: pointer;
    }

    .btn-eliminar {
        border: none;
        padding: 1rem;
        width: 100%;
        background-color: #ef4444;
        font-weight: 700;
        font-size: 1.2rem;
        color: var(--blanco);
        margin-top: 10rem;
        cursor: pointer;
    }
</style>