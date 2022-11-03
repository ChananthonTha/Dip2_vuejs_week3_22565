<template>
  <div class="home">

    <MenuComponent />
    <FooterComponent />

  </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue';

export default {
  name: 'HomeMenu',
  components: {
    MenuComponent,
    FooterComponent
  }
}
</script>
