<template>
  <section class="about">
    <div class="about__content">
      <div class="about__image">
        <img src="@/assets/images/ArthurCoelho.jpeg" alt="Minha Foto" />
      </div>
      <div class="about__description">
        <h2 class="about__title">Sobre Mim</h2>
        <p class="about__text">Olá! Meu nome é Arthur Coelho e sou um desenvolvedor web full stack de 23 anos. Sou formado em análise e desenvolvimento de sistemas e atualmente estou cursando pós-graduação em engenharia de software. Tenho paixão por criar soluções tecnológicas e estou constantemente buscando aprender e aprimorar minhas habilidades como desenvolvedor. Estou sempre animado para enfrentar novos desafios e contribuir com projetos inovadores. Seja bem-vindo ao meu portfolio e sinta-se à vontade para explorar meus projetos e entrar em contato comigo para colaborações e oportunidades!</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about__content {
  background-color: #f5f5f5;
  display: flex;
  align-items: center;
}
.about__image {
  width: 265px;
  height: 260px;
  flex-shrink: 0;
  border-radius: 50%;
  overflow: hidden;
  margin-right: 20px;
}

.about__image-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.about__description {
  flex-grow: 1;
}

.about__title {
  font-size: 24px;
  margin: 0;
}

.about__text {
  font-size: 16px;
  line-height: 1.5;
  margin: 10px 0;
}
</style>
