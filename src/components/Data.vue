<template>
    <div class="container">
        <header>
            <div class="logo"><img src="../assets/images/despertador.svg" alt=""></div>
        </header>
    </div>
</template>

<script setup>

</script>

<style scoped>

    .container{
        width: 800px;
        height: 400px;
        padding: 24px;
        background-color: hsl(0, 0%, 100%);
        margin: 0 auto;
        border-radius: 16px;
        box-shadow: 5px 6px 20px rgba(0, 0, 0, 0.082);
    }
    header{
        width: 100%;
        padding-bottom: 16px;
        display: flex;
        align-items: center;
        border-bottom: 1px solid hsl(0, 0%, 94%);
        
    }

    header img{
        width: 48px;
        height: 48px;
    }
</style>