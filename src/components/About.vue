<template>
<div class="about">
    <h1>Hello {{their_name}},This is an About Page</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur cupiditate delectus esse eveniet harum, illum impedit perspiciatis quis voluptates! Accusamus blanditiis delectus distinctio id labore odio porro tempore temporibus voluptatibus!</p>
</div>
</template>

<script>
    export default {
        name: 'Skills',
        data () {
            return {
                their_name: this.$route.params.name
            }
        },
    }
</script>

