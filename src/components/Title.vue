<template>
    <div class="title">
        <h3>{{company}}</h3>
        <h4>{{title}}</h4>
        <p>{{from}} - {{to}}</p>
    </div>
</template>

<script>
module.exports = {
    props: ['company', 'title', 'from', 'to']
}
</script>
