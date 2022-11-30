<template>
    <div>
        <ul>
            <p>Cities in Italy</p>
            <li>Venice</li>
            <li>Bologna</li>
            <li>Florence</li>
            <li>Pisa</li>
            <li>Rome</li>
            <li>Naples</li>
        </ul>
        <section class="divContainer">
            <Section1Body/>
            <Section2Body/>
            <Section3Body/>
        </section>

    </div>
</template>

<script>
import Section1Body from '@/components/Section1Body.vue';
import Section2Body from '@/components/Section2Body.vue';
import Section3Body from '@/components/Section3Body.vue';

    export default {
        name : "PageBody",
        components : {
            Section1Body,
            Section2Body,
            Section3Body,
        }
    }
</script>

<style scoped>
div{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
li{
    list-style-type: none;
}
section{
    display: grid; 
    grid-template-columns: 1fr 1fr 1fr; 
    grid-gap: 20px; 
}
</style>