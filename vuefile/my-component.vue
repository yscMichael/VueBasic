<template>
    <div class="hello">Hello {{who}} {{ title }}</div>
</template>

<script>
module.exports = {
    data: function() {
        return {
            who: 'world'
        }
    },
    props:[
        'title'
    ],
}
</script>

<style>
.hello {
    background-color: #ffe;
}
</style>