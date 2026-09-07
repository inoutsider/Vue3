<template>
    <div class="Person">
        <h3>姓名：{{ a }}</h3>
        <button>显示联系方式</button>
    </div>
</template>

<script lang="ts">
    export default {
        name: "Person",
        setup() {
            let username = "张三";
            return {
                a: username
            }
        }
    }
</script>

<style scoped>
    .person {
        background-color: rgb(224, 193, 18);
        box-shadow: 0 0 15px;
        border-radius: 15px;
        padding: 15px;
    }
</style>