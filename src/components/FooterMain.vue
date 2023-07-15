<template>
  <footer class="footer">
    <div class="footer__content">
      <div class="footer__contact">
        <h3 class="footer__title">Contato</h3>
        <ul class="footer__list">
          <li class="footer__item"><a href="arthurcoelhoob@gmail.com">arthurcoelhoob@gmail.com</a></li>
          <li class="footer__item"><a href="https://github.com/ArthurCoelhob" target="_blank">GitHub</a></li>
          <li class="footer__item"><a href="https://www.linkedin.com/in/arthur-coelho-5351441b4/" target="_blank">Linkedin</a></li>
        </ul>
      </div>
      <div class="footer__info">
        <p class="footer__name">Arthur Coelho</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #f5f5f5;
  color: #333333;
  padding: 40px 20px;
  text-align: center;
}

.footer__content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer__contact {
  margin-bottom: 20px;
}

.footer__title {
  font-size: 24px;
  margin: 0 0 10px;
}

.footer__list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer__item {
  margin-bottom: 5px;
}

.footer__item a {
  color: #333333;
  text-decoration: none;
}

.footer__name {
  font-size: 16px;
  margin: 0;
}
</style>
