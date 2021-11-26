<template>
    <section>
        <h2>Work</h2>
        <div class="pc-wrapper">
            <div class="project-cards">        
                <ProjectCard name="Project 1" desc="Information about the project" thumb="../assets/img/project/cat.jpg"/>
                <ProjectCard name="Project 1" desc="Information about the project" thumb="../assets/img/project/cat.jpg"/>
                <ProjectCard name="Project 1" desc="Information about the project" thumb="../assets/img/project/cat.jpg"/>
                <ProjectCard name="Project 1" desc="Information about the project" thumb="../assets/img/project/cat.jpg"/>
        
            </div>
        </div>


    </section>
</template>

<script>
import ProjectCard from "./ProjectCard.vue"
export default ({
    name: 'WorkSection',
    components: {
        ProjectCard
    }
})
</script>

<style scoped>
    .project-cards  {
        display: inline-grid;
        grid-template-columns: auto auto;
        grid-column-gap: 66px;
        grid-row-gap: 66px; 
    }
    .pc-wrapper {
            display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
</style>