<script>
  import CharityList from "../components/CharityList.svelte";
  import { charities } from "../data/charities.js";
  import Header from "../components/Header.svelte";
  import Welcome from "../components/Welcome.svelte";
  import Promo from "../components/Promo.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<style>
  h1 {
    font-size: 3em;
    color: brown;
  }
</style>

<Header />
<Welcome />

<CharityList {charities} />

<Promo />
<Footer />
