<template>
    <div id="contact">
        <a href="mailto:harunonsystem@gmail.com">
    <sui-button type="submit">
        <i class="far fa-envelope"></i>
        Contact me!
        </sui-button>
        </a>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.ui.button{
    width: 30%;
    margin: 10px auto;
    border-radius: 20px;
    animation: animScale 2s infinite ease-out;
    transform-origin: 50% 50%;
    animation-play-state:running;
}
.ui.button:hover{
 background-image: radial-gradient( circle 180px at 1.9% 5%, rgba(0,193,80,1) 0%, rgba(0,112,198,1) 100.2% );
}

@keyframes animScale {
0% { transform: scale(0.8, 0.8); }
5% { transform: scale(1.2, 1.2); }
10% { transform: scale(1, 1); }
15% { transform: scale(1.1, 1.1); }
20% { transform: scale(1, 1); }
100% { transform: scale(1, 1); }
}
@media screen and (max-width:480px){
    .ui.button{
        width:80%;
    }
}
</style>
