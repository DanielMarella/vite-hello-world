<script>
</script>

<template>
    <div class="jumbotron">
        <img src="../assets/flycat.jpg" alt="immagine di Top-gun Maverick presa dal film originale">
    </div>
</template>


<style scoped>
    .jumbotron{
        border: 10px solid yellow;
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

    .jumbotron{
    border: 10px solid hsl(0, 100%, 50%);
    -webkit-animation: rainbow 2s infinite alternate;
    }

    .jumbotron img{
        width: 100%;
    }

</style>


#fd004c,
#fe9000,
#fff020,
#3edf4b,
#3363ff,
#b102b7,
#fd004c