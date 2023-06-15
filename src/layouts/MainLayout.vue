<template>
  <q-layout view="hhh lpR lfr">

    <q-header reveal elevated class="bg-primary text-white">
      <q-toolbar>
        <div class="column">
          <img src="src/assets/logo.PNG" alt="" style="width: 20px;">
        </div>
        <div class="column search-column">
          <q-toolbar-title>
            <div class="search-wrapper">
              <i class="fa fa-search search-icon"></i>
              <q-input outlined placeholder="Search..." class="search-input"></q-input>
            </div>
          </q-toolbar-title>
        </div>
        <div class="column">
          <div class="column">
              <img src="src/assets/cart.PNG" alt="" style="width: 50px;">
            </div>
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<style>
.column {
  flex: 1;
  text-align: center;
  padding: 10px;
  background-color: #4655fa;
  display: flex;
  align-items: center;
  justify-content: center;
}

.search-column {
  position: relative;
}

.search-input {
  width: 100%;
}

.search-icon {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
}
</style>

<script>
import { ref } from 'vue'

export default {
  setup() {
    const leftDrawerOpen = ref(false)
    const rightDrawerOpen = ref(false)

    return {
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value
      },

      rightDrawerOpen,
      toggleRightDrawer() {
        rightDrawerOpen.value = !rightDrawerOpen.value
      }
    }
  }
}
</script>