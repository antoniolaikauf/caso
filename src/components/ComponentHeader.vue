<script>
export default {
  header: "Header"
}
</script>

<template>
<header class="sfondo">
  <nav class="display-menu">
    <!-- immagine logo -->
    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <!-- lista mesu -->
    <ul >
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
      <li>
        <a href="#">testo</a>
      </li>
    </ul>
  </nav>
</header>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;

.display-menu{
  display:$display_flex ;
  justify-content:$specific_content;
  width: $width_blocchi;
  margin:$margin_blocchi;
  align-items:$specific_align;
  padding: 20px 0px;

    ul{
      display:$display_flex ;
      justify-content:$specific_content;

      li{
        padding: 0px 10px;
      }

    }
}
</style>
