<template>
    <div id="game">
        <h2>游戏名1{{name1}}</h2>
        <h2>游戏名2{{name2}}</h2>
        <h2>游戏名3{{name3}}</h2>
        <h2>游戏名4{{name4}}</h2>
    </div>
</template>

<script>
    export default {
        name: 'Game',
        data() {
            return {
                name1: '海岸三番街',
                name2: '海上列车',
                name3: '悬空城',
                name4: '安图恩'
            }
        }
    }
</script>

<style>
    #game{
        background-color: rgb(119, 119, 180);
    }
</style>