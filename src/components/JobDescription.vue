<template>
    <div>
        <p v-for="line in description" :key="line">
        {{line}}
        </p>
    </div>
</template>

<script>
module.exports = {
    props: ['description']
}
</script>
