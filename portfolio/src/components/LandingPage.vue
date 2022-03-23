<template>
    <main>
        <HeroSection/>
        <div class="company-bar">
            <CompanyBar/>
        </div>
        <WorkSection class="work-section"/>
        <AboutMeSection/>
        <ContactSection/>

    </main>
</template>

<script>
import HeroSection from './HeroSection.vue'
import CompanyBar from './CompanyBar.vue'
import WorkSection from './WorkSection.vue'
import AboutMeSection from './AboutMeSection.vue'
import ContactSection from './ContactSection.vue'

export default  ({
    setup() {
        
    },
    name: 'LandingPage',
    components: {
        HeroSection,
        CompanyBar,
        WorkSection,
        AboutMeSection,
        ContactSection
    }
})
</script>

<style scoped>
    main    {
        margin: 0 80px;
    }
    .company-bar  {
        display: flex;
        justify-content: center;
        margin-bottom: 48px;
    }
    .work-section   {
        margin-bottom: 48px;
    }
</style>
