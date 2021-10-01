<template>
    <div class="job" v-bind:class="{current: job.isCurrent}">
        <Title :company="job.company" :title="job.title" :from="job.from" :to="job.to"></Title>
        <JobDescription></JobDescription>
        <h4>Key Skills:</h4>
        <SkillList :skills="job.skills"></SkillList>
    </div>
</template>

<script>
import Title from './Title.vue'
import JobDescription from './JobDescription.vue'
import SkillList from './SkillList.vue'

export default {
    name: 'Job',
    components: {
        Title,
        JobDescription,
        SkillList
    },
    props: ['job']
}
</script>