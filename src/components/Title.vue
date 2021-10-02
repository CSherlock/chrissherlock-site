<template>
    <div class="pb-2">
        <h3>{{company}}</h3>
        <h4>{{title}}</h4>
        <p class="italic">{{from}} - {{to}}</p>
    </div>
</template>

<script>
module.exports = {
    props: ['company', 'title', 'from', 'to']
}
</script>
