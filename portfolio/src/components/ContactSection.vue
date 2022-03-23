<template>
    <section>
        <h2>Contact</h2>
        <ContactCard/>
    </section>
</template>

<script>
import ContactCard from './ContactCard.vue'
export default ({
    name: 'ContactSection',
    components:    {
        ContactCard,
    }
})
</script>
