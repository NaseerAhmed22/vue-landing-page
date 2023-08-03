<template>
    <div id="app" class="">
       <Nav></Nav>
       <Home></Home>
       <Legal></Legal>
       <Count></Count>
       <Testimonial></Testimonial>
      <Contact></Contact>
      <Footer></Footer>

    </div>
</template>   

<script>
import Nav from './components/Nav.vue'
import Home from './components/Home.vue'
import Legal from './components/Legal.vue'
import Testimonial from './components/Testimonial.vue'
import Count from './components/Count.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
    name: 'App',
    components: {
        Nav,
        Home,
        Legal,
        Count,
        Testimonial,
        Contact,
        Footer
    }
}
</script>

<style>

</style>
