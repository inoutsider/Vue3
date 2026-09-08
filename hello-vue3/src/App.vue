<template>
    <div class="hello">
    <h1>hello vue 3!</h1>
    <Person></Person>
    </div>
</template>

<script lang="ts">
    import Person from './components/Person.vue';
    export default {
        name: "Application",
        components: {
            Person
        }
    }
</script>

<style scoped>

    .hello {
        background-color: rgb(90, 168, 142);
        box-shadow: 0 0 15px;
        border-radius: 15px;
        padding: 15px;
    }

</style>