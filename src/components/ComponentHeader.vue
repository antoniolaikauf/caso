<script>
export default {
  header: "Header",


  data() {
    return {
      links: [
        {
          text:"CHARACTERS",
          url:"#",
          current:false,
        },
        {
          text:"COMICS",
          url:"#",
          current:true,
        },
        {
          text:"MOVIES",
          url:"#",
          current:false,
        },
        {
          text:"TV",
          url:"#",
          current:false,
        },
        {
          text:"GAMES",
          url:"#",
          current:false,
        },
        {
          text:"COLLECTIBLES",
          url:"#",
          current:false,
        },
        {
          text:"VIDEOS",
          url:"#",
          current:false,
        },
        {
          text:"FANS",
          url:"#",
          current:false,
        },
        {
          text:"NEWS",
          url:"#",
          current:false,
        },
        {
          text:"SHOP",
          url:"#",
          current:false,
        },
      ]
    }
  }
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
      <ul>
        <li v-for="link in links">
          <a href="#">{{ link.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;

.display-menu {
  display: $display_flex ;
  justify-content: $specific_content;
  width: $width_blocchi;
  margin: $margin_blocchi;
  align-items: $specific_align;
  padding: 20px 0px;

  img {
    width: 60px;
  }

  ul {
    display: $display_flex ;
    justify-content: $specific_content;

    li {
      padding: 0px 10px;
    }

  }
}
</style>
