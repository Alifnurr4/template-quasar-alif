<template>
  <q-layout view="lHh lpr lFh" class="column full-height">
    <!-- Header -->
    <q-header elevated class="bg-primary text-white">
      <q-toolbar>
        <q-avatar>
          <img src="https://cdn.quasar.dev/img/avatar.png">
        </q-avatar>
        <q-toolbar-title class="text-weight-bold q-ml-sm">
          Portofolio Alif Nur Rokhman
        </q-toolbar-title>
        <q-btn round dense icon="account_circle" to="/ya" />
        <q-btn round dense icon="account_circle" />
        <q-btn round dense icon="account_circle" />
      </q-toolbar>
    </q-header>

    <div class="column fit">
      <q-page-container class="col">
        <q-page class="q-pa-md">
          <router-view />
        </q-page>
      </q-page-container>
      <footer
        v-if="showFooter"
        class="bg-grey-3 text-dark q-pt-md q-pb-md"
      >
        <div class="text-center text-caption">
          &copy; {{ new Date().getFullYear() }} Alif Rokhman. Dibuat dengan Quasar Framework.
        </div>
      </footer>
    </div>
  </q-layout>
</template>

<script>
import { defineComponent, computed } from 'vue'
import { useRoute } from 'vue-router'

export default defineComponent({
  name: 'MainLayout',
  setup() {
    const route = useRoute()

    // Tampilkan footer hanya di halaman utama (landing page)
    const showFooter = computed(() => route.path === '/')

    return { showFooter }
  }
})
</script>
