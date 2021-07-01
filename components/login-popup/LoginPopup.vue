<template>
    <div>
        <div class="layer"></div>
        <div class="main">
            <div class="header">登录</div>
        </div>
    </div>
</template>

<script>
export default {
    data () {
        return {
            
        }
    }
}
</script>

<style lang="less" scoped>
.layer {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
}
.main {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    width: 200px;
    height: 200px;
    background: #ffffff;
    border-radius: 10px;

    .header {
        text-align: center;
        padding: 10px;
        color: #000000;
    }
}
</style>
