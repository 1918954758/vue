<template>
    <!-- 模板 -->
    <div id="study">
        <h2>我在学习{{name}}</h2>
        <h2>学习了{{times}}</h2>
    </div>
</template>
    
<script>
    export default {
        name: 'Study',
        /* template: `
            <div>
                <h2>我在学习{{name}}</h2>
                <h2>学习了{{times}}</h2>
            </div>
        `, */
        data() {
            return {
                name: '数学',
                times: '45min'
            }
        }
    }
</script>


<style>
    #study{
        background-color: skyblue;
    }
</style>