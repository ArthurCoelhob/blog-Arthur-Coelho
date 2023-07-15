<template>
  <section class="skills">
    <h2 class="skills__title">Habilidades</h2>
    <ul class="skills__list">
      <li v-for="habilidade in habilidades" :key="habilidade.id" class="skills__item">
        {{ habilidade.nome }}
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      habilidades: [
        {
          id: 1,
          nome: 'PHP'
        },
        {
          id: 2,
          nome: 'Laravel'
        },
        {
          id: 3,
          nome: 'Symfony'
        },
        {
          id: 4,
          nome: 'SQL'
        },
        {
          id: 5,
          nome: 'JavaScript'
        },
        {
          id: 6,
          nome: 'Vue.js'
        },
        {
          id: 7,
          nome: 'HTML'
        },
        {
          id: 8,
          nome: 'CSS'
        },
        {
          id: 8,
          nome: 'Docker'
        },
      ]
    }
  }
}
</script>

<style scoped>
.skills {
  background-color: #f5f5f5;
  padding: 40px 20px;
  text-align: center;
}

.skills__title {
  font-size: 24px;
  margin-bottom: 20px;
}

.skills__list {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.skills__item {
  background-color: #ffffff;
  color: #333333;
  padding: 10px 20px;
  border-radius: 4px;
  margin: 5px;
  font-size: 16px;
}

</style>
