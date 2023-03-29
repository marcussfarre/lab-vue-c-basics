<script>
    export default {
        name: 'ExerciseOne',
        data() {
            return {
                firstItem: 0,
                secondItem: 0,
                result: 0,
            }
        },
        methods: {
            getResult() {
                this.result = this.firstItem + this.secondItem;
            }
        },
    }
</script>

<template>
    <div class="containerOne">
        <label for="firstItem">First item:</label>
        <input type="number" v-model="firstItem">
        <br>
        <label for="secondItem">Second item:</label>
        <input type="number" v-model="secondItem">
        <p>The result is {{ result }}</p>
        <button type="button" @click.prevent="getResult()">Action</button>
    </div>
</template>

<style scoped>
    .containerOne {
        text-align: center;
    }
</style>
