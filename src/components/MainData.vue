<template>
    <div>
        <main>
            <p><span>{{ horas }}</span>horas</p>
            <p><span>{{ minutos }}</span>minutos</p>
            <p><span>{{ segundos }}</span>segundos</p>
        </main>
    </div>
</template>
<script setup>
import { ref } from 'vue';

const horas = ref(0)
const minutos = ref(0)
const segundos = ref(0)

function getHours(){
    const currentHours = new Date()

    horas.value = currentHours.getHours()
    minutos.value = currentHours.getMinutes()
    segundos.value = currentHours.getSeconds()
}

setInterval(getHours, 1000)
</script>

<style scoped lang="scss">
    $Purple: hsl(259, 100%, 65%);
    p{
        font-family: 'poppins', sans-serif;
        font-size: 4rem;
        font-weight: 700;
        font-style: italic;

        span{
            color: $Purple;
        }
    }
</style>