<template>
    <div class="home-wrap">
        <main>
            <router-link></router-link>
        </main>
        <footer>
            <router-link to="/index">消息</router-link>
            <router-link to="/hot">列表</router-link>
            <router-link to="/scl">动态</router-link>
        </footer>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .home-wrap{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
    }
    main{
        width: 100%;
        overflow: auto;
        flex: 1;
    }
    footer{
        width: 100%;
        height: 50px;
        border-top:1px solid #ccc;
        display: flex;
        justify-content: space-around;
        align-items: center;
        a{
            text-decoration: none;
            color: #333;
        } 
    }
    .router-link-action{
        color: red;
    }
</style>


