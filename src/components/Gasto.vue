<script setup>

</script>

<template>
    <div>

    </div>
</template>

<style scoped>
    .gasto {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 2rem;
    }
    .contenido {
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .icono {
        width: 5rem;
    }
    .detalles p {
        margin: 0 0 1rem 0;
    }
    .categoria {
        color: var(--gris);
        font-size: 1.2rem;
        text-transform: uppercase;
        font-weight: 900;
    }
    .nombre {
        color: var(--gris-oscuro);
        font-size: 2.4rem;
        font-weight: 700;
        cursor: pointer;
    }
    .fecha {
        color: var(--gris-oscuro);
        font-size: 1.6rem;
        font-weight: 900;
    }
    .fecha span {
        font-weight: 400;
    }   
    .cantidad {
        font-size: 3rem;
        font-weight: 900;
        margin: 0;
    }
</style>