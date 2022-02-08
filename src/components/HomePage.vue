<template>
    <div>
        <PageHeader/>
        <div class="container-sm">
            <Introduction/>
            <div id="WorkExperience">
                <Workexperience/>
            </div>
            <div id="Skill">
                <SkillsAndAchievement/>
            </div>
            <div id="Projects">
                <Projects/>
            </div>
        </div>
        <div id="Contact">
            <Contact/>
        </div>
        
    </div>
</template>
<script>
import Workexperience from "./WorkExperience.vue";
import Introduction from "./Introduction.vue";
import SkillsAndAchievement from './SkillsAndAchievement.vue';
import PageHeader from './PageHeader.vue';
import Projects from './Projects.vue';
import Contact from './Contact.vue';
export default {
    name: "HomePage",
    components:{
        Workexperience,
        Introduction,
        PageHeader,
        SkillsAndAchievement,
        Projects,
        Contact
    }
}
</script>