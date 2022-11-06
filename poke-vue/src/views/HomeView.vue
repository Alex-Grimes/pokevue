<!-- eslint-disable vue/multi-word-component-names -->
<script>
import PokemonVue from '../components/pokemon.vue';
import axios from 'axios'
export default {
  name: "Home",
  data() {
    return {

    }
  },
  components: {
    PokemonVue,
  },
}

// axios.get("https://pokeapi.co/api/v2/pokemon/1")
//   .then((response) => {
//     poke = response
//   })
//   .catch((err) => console.log(err));

</script>

<template>
  <main>
    <pokemonVue />
  </main>
</template>
