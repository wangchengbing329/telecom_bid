<template>
    <div>
        <el-steps :active='currentStep'>
            <el-step title="Order" icon="el-icon-edit"></el-step>
            <el-step title="VMachine Config" icon="el-icon-upload"></el-step>
            <el-step title="Network Config" icon="el-icon-picture"></el-step>
        </el-steps>
        <div class='step-content'>

        </div>
        <div class='step-footer'>
            <el-button class='step-footer-button' type='primary'>下一步</el-button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            // 当前步骤
            currentStep: 0
        };
    }
};
</script>

<style lang='scss' scoped>
.step-content {
    width: 100%;
    margin-top: 20px;
    min-height: 300px;
    border: 1px solid #EBEBEB;
}

.step-footer {
    overflow: hidden;
    padding-top: 20px;

    .step-footer-button {
        float: right;
    }
}
</style>
