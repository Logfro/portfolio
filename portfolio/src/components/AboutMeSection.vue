<template>
    <section>
        <h2>About Me</h2>
        <Testimonial/>
    </section>
</template>

<script>
import Testimonial from './Testimonial.vue'
export default ({
    name: 'AboutMeSection',
    components: {
        Testimonial,
    }
})
</script>
