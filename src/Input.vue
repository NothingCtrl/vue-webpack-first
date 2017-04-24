<template>
    <div>
        <p>Binding from Message.vue: {{ msg }}</p>
        <input type="text" v-model="message"/>
        <p>{{ message }}</p>
    </div>
</template>

<script>
    export default {
        props: ['msg'],
        data() {
            return {
                message: ''
            }
        }
    }
</script>