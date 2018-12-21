/*
 * @Author: hzq
 * @Date: 2018-09-17 14:44:47
 * @Last Modified by: hzq
 * @Last Modified time: 2018-12-21 17:50:12
 * @文件说明: 新建渠道页面
 */
<template>
    <div class='add-channel'>
        我是{{msg}}
    </div>
</template>

<script>
    import { Vue, Component, Prop } from 'vue-property-decorator'
    @Component
    export default class AddChannel extends Vue {
        msg = '新建渠道页面'
    }
</script>

<style scoped lang="scss">
    .add-channel {
        height: 200px;
        color: aqua;
    }
</style>
