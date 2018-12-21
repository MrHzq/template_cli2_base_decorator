<template>
    <div class="test">我是：{{msg}}</div>
</template>

<script>
    import { Vue, Component, Prop } from 'vue-property-decorator'
    @Component
    export default class Test extends Vue {
        msg = 'Cli 2 + Base'
        created() {
            this.$api
                .login({
                    password: 'qwer1234',
                    userNo: '13402318457'
                })
                .then(res => console.log(res))
        }
    }
</script>

<style scoped lang="scss">
    .test {
        color: red;
    }
</style>
