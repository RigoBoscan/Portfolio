<template>
 <div class="pa-0">
  <hello-world />
  <section-options />
 </div>
</template>

<script>
import SectionOptions from '@/components/SectionOptions/SectionOptions.vue'
  import HelloWorld from '../components/HelloWorld/HelloWorld.vue'

  export default {
    name: 'Home',

    components: {
      HelloWorld,
        SectionOptions,
    },
  }
</script>
