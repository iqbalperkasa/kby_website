<template lang="pug">
  section
    LayoutDefault
      h2.mb-30.heading.text-align-center Konfirmasi Donasi
      p.mb-10 Halo sobat, terima kasih sudah menyisihkan rezeki kamu untuk berbagi. Selanjutnya silakan isi form di bawah supaya dapat kami rekap ya. Terima kasih.
      iframe.form(
        ref='mainForm'
        src='https://form.jotform.com/201028295899062'
      )
</template>

<script>
import LayoutDefault from 'src/layouts/default';

export default {
  name: 'Confirmation',
  components: {
    LayoutDefault,
  },
}
</script>

<style lang="stylus" scoped>
.form
  width 100%
  height 1000px
  border none
  overflow hidden
</style>
