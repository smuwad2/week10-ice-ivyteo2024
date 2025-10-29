<script>
    export default { 
        data() {
            return {
                soundEmojis: ['🔇', '🔈', '🔉', '🔊']
            }
        },
        // TODO: add code to define a necessary prop
        props:{ //take in a property from the parent 
            level: Number
        }
    }
</script>

<template>
    <!-- TODO: add your template code here. Use span element. --> 
    <span>
        {{soundEmojis[level]}}
    </span>
</template>