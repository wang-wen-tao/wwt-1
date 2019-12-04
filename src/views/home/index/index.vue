<template>
    <div class="index-wrap">
        <header>
            <p>
                <input type="text" placeholder="搜索">
            </p>
        </header>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .index-wrap{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
    }
    header{
        width: 100%;
        height: 50px;
        display: flex;
        border-bottom: 1px solid #ccc;
        p{
            flex: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            input{
                width: 90%;
                height: 60%;
                border-redius:5px;
                outline: none;
                border: 1px solid #ccc;
            }
        }
    }
</style>

