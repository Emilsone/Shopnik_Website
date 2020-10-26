<template>
  <div>
    <hero />
    <features />
    <prices />
    <stylish />
    <product />
    <suscribe />
  </div>
</template>

<script>
import Hero from '@/components/Hero'
import Features from '@/components/Features'
import Prices from '@/components/Prices'
import Stylish from '@/components/Stylish'
import Product from '@/components/Product'
import Suscribe from '@/components/Suscribe'

export default {
  name: 'LandingPage',
  components: {
    hero: Hero,
    features: Features,
    prices: Prices,
    stylish: Stylish,
    product: Product,
    suscribe: Suscribe,
  }
}
</script>
