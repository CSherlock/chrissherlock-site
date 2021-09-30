<template>
    <div class="keyskills">
        <Skill skill='C#'></Skill>
        <Skill skill='Python'></Skill>
        <Skill skill='Manual Testing'></Skill>
    </div>
</template>

<script>
import Skill from './Skill.vue'

export default {
    name: 'SkillList',
    components: {
        Skill
    }
}
</script>
