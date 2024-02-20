<script>
import { store } from './store';
import axios from 'axios';

// IMPORTIAMO LE APP 

import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppCard from './components/AppCard.vue';



export default {
  data() {
    return {

    };
  },

  // COMPONENTS

  components: { AppHeader, AppMain, AppCard, AppFooter },
};

</script>
