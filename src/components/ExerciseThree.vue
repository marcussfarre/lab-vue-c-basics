<script>
    export default {
        name: 'ExerciseThree',
        data() {
            return {
                notices: [
                    {
                        title: 'First notice',
                        description: 'lorem ipsum',
                        content: 'aaa'
                    },
                    {
                        title: 'Second notice',
                        description: 'lorem ipsum',
                        content: 'bbb'
                    },
                    {
                        title: 'Three notice',
                        description: 'lorem ipsum',
                        content: 'ccc'
                    },
                ]
            }
        },
        methods: {
            
        }
    }
</script>

<template>
    <div class="containerThree">
        <div v-for="notice in notices">
            <p>Title: {{ notice.title }}</p>
            <p>Description: {{ notice.description }}</p>
            <p>Content: {{ notice.content }}</p>
        </div>
    </div>
</template>

<style scoped>
    .containerThree {
        text-align: center;
    }
</style>
