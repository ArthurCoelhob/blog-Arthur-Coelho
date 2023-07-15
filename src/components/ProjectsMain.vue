<template>
  <section class="projects">
    <h2 class="projects__title">Projetos</h2>
    <ul class="projects__list">
      <li v-for="projeto in projetos" :key="projeto.id" class="projects__item">
        <h3 class="projects__item-title">{{ projeto.nome }}</h3>
        <p class="projects__item-description">{{ projeto.descricao }}</p>
        <a :href="projeto.url" target="_blank" class="projects__item-link">Veja o projeto</a>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projetos: [
        {
          id: 1,
          nome: 'Agenda Telefonica',
          descricao: 'Criação de uma aplicação que permite incluir contatos a uma agenda telefonica',
          url: 'https://github.com/ArthurCoelhob/AgendaTelefonica'
        },
        {
          id: 2,
          nome: 'ApiBuscaDev',
          descricao: 'Criação de uma API que permite inserir e buscar por desenvolvedores',
          url: 'https://github.com/ArthurCoelhob/ApiBuscaDev'
        },
        {
          id: 3,
          nome: 'CompanyConsult',
          descricao: 'Criação de uma API que permite inserir e buscar por funcionarios de yuma empresa',
          url: 'https://github.com/ArthurCoelhob/CompanyConsult'
        },
      ]
    }
  }
}
</script>

<style scoped>
.projects {
  background-color: #f5f5f5;
  padding: 40px 20px;
  text-align: center;
}

.projects__title {
  font-size: 24px;
  margin-bottom: 20px;
}

.projects__list {
  list-style: none;
  padding: 0;
  margin: 0 auto;
  max-width: 800px;
}

.projects__item {
  background-color: #ffffff;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  padding: 20px;
  margin-bottom: 20px;
}

.projects__item-title {
  font-size: 20px;
  margin: 0;
}

.projects__item-description {
  margin-top: 10px;
}

.projects__item-link {
  display: inline-block;
  margin-top: 20px;
  background-color: #333333;
  color: #ffffff;
  padding: 10px 20px;
  border-radius: 4px;
  text-decoration: none;
}

.projects__item-link:hover {
  background-color: #555555;
}
</style>
