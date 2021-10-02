<template>
    <div id='app'>
        <main>
            <Header></Header>
            <div class="flex flex-col text-center p-0 md:p-12 justify-center">
                <Profile></Profile>
                <Experience :jobs="jobs"></Experience>
            </div>
        </main>
        <Footer></Footer>
    </div>
</template>

<script>
import Header from './components/Header.vue'
import Profile from './components/Profile.vue'
import Experience from './components/Experience.vue'
// import MobileNavbar from './components/MobileNavbar.vue'
// import Content from './components/Content.vue'
import Footer from './components/Footer.vue'
import jobs from './util/jobs.json';

export default {
  name: 'App',
  components: {
    Header,
    Profile,
    Experience,
    Footer
  },
  data() {
    return {
      jobs: jobs,
    }
  }
}
</script>
