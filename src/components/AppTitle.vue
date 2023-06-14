<script>

</script>


<template>
    <div class="header">
        <h1 class="rainbow-text">La mia prima app con Vite!!!!!!!</h1>
    </div>


</template>


<style scoped>

    h1{
        font-size: 3rem;
    }

    .rainbow-text {
    background-image: linear-gradient(to left, violet, indigo, blue, green, yellow, orange, red); 
    background-clip: text;
    color: transparent;
    }

    .header{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 50rem;
        height: 10rem;
        border: 10px solid purple;
        background-color: black;
    }
</style>