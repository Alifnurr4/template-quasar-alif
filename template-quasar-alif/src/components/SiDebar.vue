<template>
  <q-drawer show-if-above side="left" class="bg-primary text-white" elevated>
    <q-list>
      <!-- Profil Pengguna -->
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://via.placeholder.com/40" alt="User Avatar" />
          </q-avatar>
        </q-item-section>
        <q-item-section>
          <q-item-label class="text-bold">Pengguna</q-item-label>
          <q-item-label caption>Profil</q-item-label>
        </q-item-section>
      </q-item>

      <q-separator color="white" />

      <!-- Menu Utama -->
      <template v-if="!showKeuangan">
        <q-item clickable v-ripple>
          <q-btn flat class="full-width text-left" @click="toggleKeuangan"
            >Administrasi</q-btn
          >
        </q-item>
        <q-item clickable v-ripple>
          <q-btn
            flat
            class="full-width text-left"
            color="green"
            @click="toggleKeuangan"
            >Keuangan</q-btn
          >
        </q-item>
      </template>

      <!-- Sub-menu Keuangan -->
      <template v-else>
        <q-item clickable v-ripple @click="toggleKeuangan">
          <q-item-section avatar>
            <q-icon name="home" />
          </q-item-section>
          <q-item-section>Keuangan</q-item-section>
        </q-item>

        <q-item clickable v-ripple>
          <q-item-section>📄 ePPST</q-item-section>
        </q-item>
        <q-item clickable v-ripple>
          <q-item-section>📄 eBAHP</q-item-section>
        </q-item>
        <q-item clickable v-ripple>
          <q-item-section>📄 eBAST</q-item-section>
        </q-item>
        <q-item clickable v-ripple>
          <q-item-section>📄 eBAPP</q-item-section>
        </q-item>
      </template>
    </q-list>

    <!-- Tombol Bawah -->
    <div class="absolute bottom-0 w-full p-4">
      <q-btn
        color="grey-8"
        class="full-width q-mb-sm"
        label="ABSEN"
        icon="fiber_manual_record"
      />
      <q-btn color="red-7" class="full-width" label="LOGOUT" icon="logout" />
    </div>
  </q-drawer>
</template>

<script>
export default {
  data() {
    return {
      showKeuangan: false,
    };
  },
  methods: {
    toggleKeuangan() {
      this.showKeuangan = !this.showKeuangan;
    },
  },
};
</script>

<style scoped>
.full-width {
  width: 100%;
}
</style>
