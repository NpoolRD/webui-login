<template>
    <div class="login-main">
        <loginframe class="login-frame"></loginframe>
    </div>
</template>
<script>
module.exports = {
    components: {
        'loginframe': httpVueLoader('../login/login-frame.vue')
    }
}
</script>
<style scoped>
.login-frame {
    width: 30%;
    height: 30%;
    margin: auto;
    border-radius: 5px;
}
.login-main {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-image: url('../res/bg/common.bg.jpeg'); 
    background-attachment: scroll; 
    background-repeat: no-repeat;
    background-size:100% 100%;
}
</style>