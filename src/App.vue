<template>
    <div id="app">
        <div class='main'>
            <header class='header'>
                <div class='container'></div>
            </header>
            <div class='container'>
                <router-view />
            </div>
        </div>
    </div>
</template>

<style lang="scss">
.header {
    height: 80px;
    width: 100%;

    .container {
        height: 100%;
        box-sizing: border-box;
        border-bottom: 1px solid #dcdfe6;
    }
}

.container {
    width: 1140px;
    margin: 20px auto;
    height: 100%;
}
</style>
