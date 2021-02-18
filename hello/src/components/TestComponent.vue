<template>
    <div>
    <h1>Hello {{username}}</h1>
    <h3>Welcome to my first vue app </h3> 
    </div>
</template>

<script>
export default {
    name:"TestComponent",
    props: {
        username:String
    }
}

</script>