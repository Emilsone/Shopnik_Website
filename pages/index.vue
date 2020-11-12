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
import Delivery from '@/components/Delivery'
import Suscribe from '@/components/Suscribe'

export default {
  name: 'LandingPage',
  components: {
    Hero,
    Features,
    Prices,
    Stylish,
    Delivery,
    Suscribe
  }
}
</script>
