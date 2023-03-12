<template>
    <div class="playGame">
        <h2>我在玩{{name}}</h2>
        <h2>打算要玩{{times}}</h2>
        <Game></Game>
    </div>
</template>

<script>
    import Game from './Game'
    
    export default {
        name: 'PlayGame',
        // template: `
        //     <div>
        //         <h2>我在玩{{name}}</h2>
        //         <h2>打算要玩{{times}}</h2>
        //         <Game></Game>
        //     </div>
        // `,
        data() {
            return {
                name: 'DNF',
                times: '45min'
            }
        },
        components: {
            Game
        }
    }
</script>


<style>
    .playGame{
        background-color: red;
        margin-bottom: 5%;
    }
</style>