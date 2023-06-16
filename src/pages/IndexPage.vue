<template>
  <q-page class="flex flex-center">
    <q-layout view="lHh Lpr lFf">
      <q-page-container>
        <q-page class="flex flex-center">
          <!-- <first-link /> -->
          <second-link />
          <third-link />
        </q-page>
      </q-page-container>
    </q-layout>
  </q-page>
</template>
<script>

import { defineComponent } from 'vue'
//import FirstLink from 'src/components/FirstLink.vue'
import SecondLink from 'src/components/SecondLink.vue'
import ThirdLink from 'src/components/ThirdLink.vue'

export default defineComponent({
  name: 'IndexPage',
  components : {
    //FirstLink,
    SecondLink,
    ThirdLink
  }
})
</script>
