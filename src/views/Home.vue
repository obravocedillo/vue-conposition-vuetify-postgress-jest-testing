<template>
  <div class="home">
    <Navbar />
    <ServersList />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Navbar from '../components/Navbar.vue'; // @ is an alias to /src
import ServersList from '../components/ServersList.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'Home',
  components: {
    Navbar,
    ServersList,
  },
});
</script>
