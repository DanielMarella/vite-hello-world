<script>

</script>


<template>
    <div class="header rainbow-border">
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


    @-webkit-keyframes rainbow {
    0% {border-color: #fd004c;}
    15% {border-color: #fe9000;}
    30% {border-color: #fff020;}
    45% {border-color: #3edf4b;}
    60% {border-color: #3363ff;}
    75% {border-color: #b102b7;}
    100% {border-color: hsl(255, 100%, 50%);}
    }

    .rainbow-border{
    border: 10px solid hsl(0, 100%, 50%);
    -webkit-animation: rainbow 2s infinite alternate;
    }

</style>