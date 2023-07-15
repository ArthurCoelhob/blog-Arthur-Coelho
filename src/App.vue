<template>
  <div>
    <Header />
    <main>
      <About />
      <Projects />
      <Skills />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './components/HeaderMain.vue'
import About from './components/AboutMain.vue'
import Projects from './components/ProjectsMain.vue'
import Skills from './components/SkillsMain.vue'
import Footer from './components/FooterMain.vue'

export default {
  components: {
    Header,
    About,
    Projects,
    Skills,
    Footer
  }
}
</script>

<style>
</style>