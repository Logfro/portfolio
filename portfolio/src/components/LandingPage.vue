<template>
    <main>
        <HeroSection/>
    </main>
</template>

<script>
import HeroSection from './HeroSection.vue'

export default  ({
    setup() {
        
    },
    name: 'LandingPage',
    components: {
        HeroSection
    }
})
</script>

<style scoped>
    main    {
        margin: 0 80px;
    }
</style>
