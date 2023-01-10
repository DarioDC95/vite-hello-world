<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            message: 'La mia prima app con Vite!'
        }
    } 
}
</script>

<template>
    <div class="intro">
        {{message}}
    </div>
</template>

<style>
    .intro {
        font-size: 30px;
        color: grey;
        padding: 30px 45px;
        background-color: #EEEEEE;
        border-radius: 7px;
    }
</style>