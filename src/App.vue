<template>
  <div>
    <CoverTop/>
    <NavBar/>
      
      <AboutSection/>
      <SocialIcons/>
      <EducationSection/>
      <ExperienceSection/>
      <CertificateSection/>
      <SkillsSection/>
      <ContactSection/>
      
      
      
    <FooterSection/>
  </div>
</template>

<script>
import CoverTop from './components/CoverTop.vue'
import NavBar from './components/NavBar.vue'
import AboutSection from './components/AboutSection.vue'
import SocialIcons from './components/SocialIcons.vue'
import EducationSection from './components/EducationSection.vue'
import ExperienceSection from './components/ExperienceSection.vue'
import CertificateSection from './components/CertificateSection.vue'
import SkillsSection from './components/SkillsSection.vue'
import ContactSection from './components/ContactSection.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    CoverTop, 
    NavBar, 
    AboutSection, 
    SocialIcons, 
    EducationSection, 
    ExperienceSection, 
    CertificateSection, 
    SkillsSection, 
    ContactSection, 
    FooterSection
  }
}
</script>

<style>

</style>
