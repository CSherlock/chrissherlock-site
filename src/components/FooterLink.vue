<template>
    <a :href="link" target="_blank" rel="noopener">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path :d="svg"/></svg>
    </a>
</template>

<script>
module.exports = {
    props: ['link', 'svg', 'name']
}
</script>
