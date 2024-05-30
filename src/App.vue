<template>
  <div class="wrapper-main">
    <Loader :loading="loading" />
    <div>
      <Header />
      <WelcomeModule />
      <Services />
      <div class="alert-wrapper-phone card-c">
          <p class="color-pink">Примечание: </p>
          <p >
              За более подробной информации можете обратиться по номеру телефона или в нашей группе в “ВК”
          </p>
      </div>
      <AboutUs/>
      <Map/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import WelcomeModule from '@/components/WelcomeModule.vue';
import Services from '@/components/Services.vue';
import Loader from '@/components/Loader.vue';
import AboutUs from './components/AboutUs.vue';
import Footer from '@/components/Footer.vue'
import Map from '@/components/Map.vue'

import './assets/scss/bootstrap.scss'


export default {
  name: 'AreaWD-project',
  data() {
    return {
      fio: '',
      rank: '',
      telegram: '',
      email: '',
      dateRegister: '',
      loading: true
    };
  },
  components: {
    Services,
    Header,
    WelcomeModule,
    Loader,
    AboutUs,
    Map,
    Footer
  },
}
</script>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
