<script>
    export default {
        name: 'ExerciseTwo',
        data() {
            return {
                isTrue: true,
            }
        },
        methods: {
            changeTrue() {
                this.isTrue = true;
            },
            changeFalse() {
                this.isTrue = false;
            },
        }
    }
</script>

<template>
    <div class="containerTwo">
        <p v-if="isTrue">True Element</p>
        <p v-else>False Element</p>
        <button @click.prevent="changeTrue()">True</button>
        <button @click.prevent="changeFalse()">False</button>
    </div>
</template>

<style scoped>
    .containerTwo {
        text-align: center;
    }
</style>
