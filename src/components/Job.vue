<template>
    <div class="border-left my-12 mx-0 md:mx-20 text-left pl-5 mb-12" v-bind:class="{current: job.current}">
        <Title :company="job.company" :title="job.title" :from="job.from" :to="job.to"></Title>
        <JobDescription :description="job.description"></JobDescription>
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
