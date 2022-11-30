<template>
    <div>
        <iframe width="560" 
            height="315" 
            src="https://www.youtube.com/embed/zS4AP0Q8L8g" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>
    </div>
</template>

<script>
    export default {
        name : "Section3Body"
    }
</script>

<style scoped>
div{
    background-color: rgb(204, 243, 255);
    box-shadow: 0 0 0 3px pink;
}
iframe{
    padding: 20px;
}
</style>