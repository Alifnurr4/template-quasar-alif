<template>
  <div class="q-pa-sm" style="background-color: rgb(247, 247, 247);">
    <div class="column items-center">
      <div class="text-h6 q-mb-lg">
        Selamat datang di Dashboard e-Program
      </div>
      <div class="text-h6 q-mb-lg">
        Selamat datang di Dashboard e-Program
      </div>
      <div class="text-h6 q-mb-sm">
        Selamat datang di Dashboard e-Program
      </div>
    </div>
  </div>


  <div class="row flex flex-center q-pa-sm">
    <div class="col-4">
      <q-img
        src="lib/images/gambar-video-handal.png"
        class="text-shadow"
        style="width: 100%; border-radius: 20px;"
      />
    </div>
    <div class="col-12 col-md-6 q-mt-xl q-pa-xl">
      <div class="text-h5 text-bold q-mb-md" style="text-align: justify;">e-Program merupakan alat bantu dalam menyusun rencana program pembangunan jalan</div>
      <div class="text-h7 q-my-md" style="text-align: justify;">Tersedia untuk meningkatkan efisiensi proses pengelolaan data geospasial, guna mendukung tata kelola ruang yang lebih baik, melalui platform arsitektur data untuk pengelolaan dan analisis spasial, yang dapat membantu dalam akuisisi dan pengelolaan data, hingga analisis dan visualisasi data</div>
      <q-btn color="primary" label="Primary" />
    </div>
  </div>

  <div class="row flex flex-center q-pa-sm" style="background-color: rgb(247, 247, 247);">
    <div class="col-12 q-py-xl q-px-xl">
      <div class="text-h5 text-bold">Mengapa e-Program</div>
    </div>
    <div class="col-12 col-md-6 responsive-padding q-py-md">
      <div class="q-item q-item-type row no-wrap" role="listitem">
        <div class="q-avatar rounded-borders q-mr-md">
          <div class="q-avatar__content row flex-center overflow-hidden">
            <img src="https://picsum.photos/500/300">
          </div>
        </div>
        <div class="q-item__section column q-item__section--main justify-center">
          <div class="q-item__label text-h6 text-bold">Peta Input Lokasi rencana pembangunan</div>
          <div class="q-item__label text-h8" style="text-align: justify;">Peta Input Lokasi rencana pembangunan.</div>
        </div>
      </div>
    </div>
    <div class="col-12 col-md-6 responsive-padding q-py-md">
      <div class="q-item q-item-type row no-wrap" role="listitem">
        <div class="q-avatar rounded-borders q-mr-md">
          <div class="q-avatar__content row flex-center overflow-hidden">
            <img src="https://picsum.photos/500/300">
          </div>
        </div>
        <div class="q-item__section column q-item__section--main justify-center">
          <div class="q-item__label text-h6 text-bold">Pembobotan Ruas rencana pembangunan</div>
          <div class="q-item__label text-h8" style="text-align: justify;">Pembobotan Ruas rencana pembangunan.</div>
        </div>
      </div>
    </div>
    <div class="col-12 col-md-6 responsive-padding q-pt-md q-pb-xl">
      <div class="q-item q-item-type row no-wrap" role="listitem">
        <div class="q-avatar rounded-borders q-mr-md">
          <div class="q-avatar__content row flex-center overflow-hidden">
            <img src="https://picsum.photos/500/300">
          </div>
        </div>
        <div class="q-item__section column q-item__section--main justify-center">
          <div class="q-item__label text-h6 text-bold">Manajemen data rencana pembangunan</div>
          <div class="q-item__label text-h8" style="text-align: justify;">Manajemen data rencana pembangunan.</div>
        </div>
      </div>
    </div>
    <div class="col-12 col-md-6 responsive-padding q-pt-md q-pb-xl">
      <div class="q-item q-item-type row no-wrap" role="listitem">
        <div class="q-avatar rounded-borders q-mr-md">
          <div class="q-avatar__content row flex-center overflow-hidden">
            <img src="https://picsum.photos/500/300">
          </div>
        </div>
        <div class="q-item__section column q-item__section--main justify-center">
          <div class="q-item__label text-h6 text-bold">Skenario dan exercise program pembangunan</div>
          <div class="q-item__label text-h8" style="text-align: justify;">Skenario dan exercise program pembangunan.</div>
        </div>
      </div>
    </div>
  </div>

  <div class="row flex flex-center q-pa-sm">
    <div class="col-12 q-py-xl q-px-xl column items-center">
      <div class="text-h5 text-bold">Fitur e-Program</div>
    </div>

    <div class="row q-col-gutter-md justify-center">
      <div class="col-12 col-sm-6 col-md-3">
        <q-card flat bordered class="q-pa-md bg-white full-height">
          <q-card-section class="text-center">
            <div class="text-body2">
              Peta Input Lokasi<br>rencana pembangunan
            </div>
          </q-card-section>
        </q-card>
      </div>

      <div class="col-12 col-sm-6 col-md-3">
        <q-card flat bordered class="q-pa-md bg-white full-height">
          <q-card-section class="text-center">
            <div class="text-body2">
              Pembobotan Ruas<br>rencana pembangunan
            </div>
          </q-card-section>
        </q-card>
      </div>

      <div class="col-12 col-sm-6 col-md-3">
        <q-card flat bordered class="q-pa-md bg-white full-height">
          <q-card-section class="text-center">
            <div class="text-body2">
              Manajemen data<br>rencana pembangunan
            </div>
          </q-card-section>
        </q-card>
      </div>

      <div class="col-12 col-sm-6 col-md-3">
        <q-card flat bordered class="q-pa-md bg-white full-height">
          <q-card-section class="text-center">
            <div class="text-body2">
              Skenario dan exercise<br>program pembangunan
            </div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
</style>
