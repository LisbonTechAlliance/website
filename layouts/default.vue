<template>
  <div>
    <nuxt/>
    <Menu />
    <footer id="page-footer">
      <p>Tema personalizado da empresa Opsou.</p>
      <a
        href="https://vigotech.org"
        class="vigotech-claim vigotech-dark">
        Adaptado do tema criado por <i class="vt-pinecone" /> em <strong>Vigo</strong>
      </a>
    </footer>
  </div>
</template>

<script>
  import Menu from '~/components/Menu'
  export default {
    components: {
      Menu
    }
  }
</script>
