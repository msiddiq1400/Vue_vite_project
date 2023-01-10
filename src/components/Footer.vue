<template>
    <div>
        <p>{{ title }}</p>
        <img src="../assets/vue.svg" alt="vue logo"/>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Footer [H: 40px]'
        }
    }
}
</script>

<style scoped>
div {
    height: 40px;
    width: 100%;
    position: fixed;bottom: 0;left: 0;
    background: #FF8066;color: #F9F871;
    display: flex;flex-direction: row;
    align-items: center;justify-content: center;
}
img {
    max-height: 35px;max-width: 35px;margin-left: 5px;
}
</style>
