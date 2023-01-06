<template>
    <div>
        <h1>Praise The LORD</h1>

        <p>The time is {{ time }}</p>
    </div>
</template>

<script>
export default {
    name: 'app',
    data(){
        return {time: new Date().toString()}
    }
}
</script>