<template lang="pug">
  #app.section
    .div
      header.hero
        .hero-body 
          .columns.sombra
            .column.center-item
              figure.imageis-128x128
                img(src="https://FernandoSotoBetin.github.com/movie/dist/moviees.jpg")
            .column.center-item
              input.input(type='text', placeholder='Buscar tu peli, actor, actriz o director favorito')
            .column
              .navbar-end
                span.navbar-item Fernando Soto
                figure.navbar-item.image.is-48x48
                  img(src="https://FernandoSotoBetin.github.com/movie/dist/loro.png")
                span.navbar-item 
                  img(src="https://FernandoSotoBetin.github.com/movie/dist/ic_arrow_drop_down_black_24px.svg")
    .div
      article.media
        aside.media-left
          .navbar.dis.color
            .navbar-brand.block
              .navbar-item.block.cen
                a
                  figure.image
                    img(src="./assets/ic_home_white_24px.svg")
                  | Home
              .navbar-item.block.cen  
                a 
                  figure.image
                    img(src="https://FernandoSotoBetin.github.com/movie/dist/ic_card_giftcard_white_24px.svg")
                  | Trending
              .navbar-item.block.cen  
                a 
                  figure.image
                    img(src="https://FernandoSotoBetin.github.com/movie/dist/ic_favorite_white_24px.svg")
                  | Más likes
            .navbar-end
              .navbar-item.block.cen
                a 
                  figure.image
                    img(src="https://FernandoSotoBetin.github.com/movie/dist/ic_settings_white_24px.svg")
                  | Ajustes
        aside.media-content
          div
            p.ptb Ahora en el Cine
            div.dis-sb
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes                
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes
          div
            p.ptb Aclamadas por la critica
            div.dis-sb
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes                
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes 
          div
            p.ptb No te debes perder
            div.dis-sb
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes                
              .card.in
                .div.card-pos
                  h1.title.is-5 The Secret Lifes of Pets
                  p the quiet life of a terrier named Max is upended when is owner takes, in Duke a stray whom instantly dislikes
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<style lang="scss">
  @import '~bulma/bulma';
  @import url('https://fonts.googleapis.com/css?family=Lato:700 | Indie+Flower');
  @import './scss/main.scss';
</style>
