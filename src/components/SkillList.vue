<template>
    <div class="content-center justify-start flex flex-wrap">
        <Skill v-for="skill in skills" :key="skill"
            v-bind:skill="skill"
        >
        </Skill>
    </div>
</template>

<script>
import Skill from './Skill.vue'

export default {
    name: 'SkillList',
    components: {
        Skill
    },
    props: ['skills']
}
</script>
