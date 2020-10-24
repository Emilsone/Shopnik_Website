<template>
  <div>
    <hero />
    <features />
    <teasers />
    <prices />
    <stylish />
    <product />
    <suscribe />
  </div>
</template>

<script>
import Hero from '@/components/Hero'
import Features from '@/components/Features'
import Teasers from '@/components/Teasers'
import Prices from '@/components/Prices'
import Stylish from '@/components/Stylish'
import Product from '@/components/Product'
import Suscribe from '@/components/Suscribe'

export default {
  name: 'LandingPage',
  components: {
    hero: Hero,
    features: Features,
    teasers: Teasers,
    prices: Prices,
    stylish: Stylish,
    product: Product,
    suscribe: Suscribe,
  }
}
</script>
