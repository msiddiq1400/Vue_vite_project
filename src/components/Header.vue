<template>
    <div>
        <img src="../assets/vite.svg" alt="vite logo"/>
        <h2>{{title}}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Header [H: 60px]'
        }
    }
}
</script>

<style scoped>
div {
    height: 60px;
    width: 100%;
    position: fixed;top: 0;left: 0;
    background: #0089BA;color: white;
    display: flex;flex-direction: row;
    align-items: center;justify-content: center;
}
img {
    max-height: 50px;max-width: 50px;margin-right: 10px;
}
</style>
