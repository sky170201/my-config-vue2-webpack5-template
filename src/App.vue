<template>
    <div>
        <h2>App</h2>
        <h3>{{ name }}</h3>
        <h4>h4标签</h4>
    </div>
</template>

<script>
export default {
    name: 'App',
    data() {
        return {
            name: 'candy'
        }
    },
    created() {
        console.log('console app created hook')
    }
}
</script>
<style lang="scss" scoped>
h4 {
    transform: rotate(45deg);
    background-color: aquamarine;
}
</style>