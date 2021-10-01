<template>
    <div id='app'>
        <main>
            <Header></Header>
            <div class="main">
                <Profile></Profile>
                <Experience :jobs="[{title:'foo', skills:['foo', 'bar'], isCurrent:true}, {title:'bar'}]"></Experience>
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

export default {
  name: 'App',
  components: {
    Header,
    Profile,
    Experience,
    Footer
  }
}
</script>