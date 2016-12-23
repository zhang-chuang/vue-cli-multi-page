<template>

<header id="header">

{{title}}

</header>

</template>

<script>

import Lib from 'assets/js/Lib.js'

module.exports = {
    props:{
        "title":{
            type:String,
            default:"标题"
        }
    }
}
</script>


<style scoped>


</style>
