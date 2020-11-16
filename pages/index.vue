<template>
  <div>
    <hero />
    <features />
    <products />
    <stylish />
    <delivery />
    <suscribe />
  </div>
</template>

<script>
import Hero from '@/components/Hero'
import Features from '@/components/Features'
import Products from '@/components/Products'
import Stylish from '@/components/Stylish'
import Delivery from '@/components/Delivery'
import Suscribe from '@/components/Suscribe'

export default {
  name: 'LandingPage',
  components: {
    Hero,
    Features,
    Products,
    Stylish,
    Delivery,
    Suscribe
  }
}
</script>
