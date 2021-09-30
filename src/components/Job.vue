<template>
    <div class="job">
        <Title company='Thales e-Security' title='Graduate Test &amp; Integration Engineer' from='September 2014' to='March 2017'></Title>
        <p>
            Joining as a graduate, I worked as part of the Test & Integration team in Cambridge. We worked alongside scrum teams tasked
            with creating new features for use with Thales e-Security Hardware Security Modules (HSMs).
        </p>
        <p>
            This work involved a lot of functional manual testing of new features, as well as maintaining and updating an automated test
            regression pack to be run as a first step towards Continuous Integration, written in C#. I also assisted with the maintenance of
            other testing helpers, which mainly were developed using Python.
        </p>
        <p>
            Outside of my day-to-day work, I was the site STEM outreach ambassador, which entailed helping out for various STEM activities, including
            organising work experience placements, and representing the company at the Big Bang Fair in Birmingham.
        </p>
        <h4>Key Skills:</h4>
        <SkillList></SkillList>
    </div>
</template>

<script>
import Title from './Title.vue'
import SkillList from './SkillList.vue'

export default {
    name: 'Job',
    components: {
        Title,
        SkillList
    }
}
</script>