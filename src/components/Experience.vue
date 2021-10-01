<template>
    <div class="experience">
        <Job v-for="job in jobs" :key="job.index"
            v-bind:job="job"
        >
        </Job>
    </div>
</template>

<script>
import Job from './Job.vue';

export default {
    name: 'Experience',
    components: {
        Job
    },
    props: ['jobs']
}
</script>