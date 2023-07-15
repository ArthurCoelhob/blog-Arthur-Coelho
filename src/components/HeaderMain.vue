<template>
  <header class="header">
    <div class="header__content">
      <h1 class="header__title">Arthur Coelho - Desenvolvedor Full Stack</h1>
      <nav class="header__nav">
        <ul class="header__nav-list">
          <li class="header__nav-item"><a href="#inicio">Início</a></li>
          <li class="header__nav-item"><a href="#sobre">Sobre</a></li>
          <li class="header__nav-item"><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background-color: #f5f5f5;
  color: #333333;
  padding: 20px;
  text-align: center;
}

.header__content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.header__title {
  font-size: 32px;
  margin: 0;
}

.header__nav {
  margin-top: 20px;
}

.header__nav-list {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
}

.header__nav-item {
  margin: 0 10px;
}

.header__nav-item a {
  color: #333333;
  text-decoration: none;
  font-size: 16px;
}

.header__nav-item a:hover {
  text-decoration: underline;
}
</style>