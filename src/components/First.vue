<template>
    <div>
        <h1>{{msg}}</h1>
    </div>
</template>

<style scoped>
    h1 {
        color: white;
        padding: 10px 50px;
        background-color: #6faf00;
    }
</style>

<script>
export default {
    name: "First",
    props: {
        msg: String
    }
}
</script>