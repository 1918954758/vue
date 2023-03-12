<template>
    <div>
        <img src="./assets/logo.png" alt="logo">
        <PlayGame></PlayGame>
        <Study></Study>
    </div>
</template>


<script>
    import PlayGame from './components/PlayGame.vue'
    import Study from './components/Study.vue'

    export default {
        name: 'App',
        // template: `
        //     <div>
        //         <img src="./assets/logo.png" alt="logo">
        //         <PlayGame></PlayGame>
        //         <Study></Study>
        //     </div>
        // `,
        components: {
            PlayGame,
            Study
        }
    }
</script>