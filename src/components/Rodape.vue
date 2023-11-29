<template>
  <footer class="app__footer">
    <section class="app__footer-sobre">
      <p class="app__footer-text">&copy; 2023 Matheus Costa Vaz.</p>
    </section>
    <section class="app__footer-contatos">
      <ul class="app__footer-redes-sociais">
        <p>
          <code
            ><a
              href="https://www.linkedin.com/in/matheuscostavaz"
              target="_blank"
              ><img
                height="30"
                src="https://img.shields.io/badge/in%2FMatheusCostaVaz-263A29?style=for-the-badge&logo=linkedin&logoColor=blue"
                alt="https://www.linkedin.com/in/matheuscostavaz" /></a
          ></code>

          <code
            ><a href="https://instagram.com/matheuxvaz" target="blank"
              ><img
                height="30"
                src="https://img.shields.io/badge/@matheuxvaz-263A29?style=for-the-badge&logo=instagram"
                alt="matheuxvaz" /></a
          ></code>

          <code
            ><a href="mailto:matheuscostav@outlook.com" target="blank"
              ><img
                height="30"
                src="https://img.shields.io/badge/matheuscostav%40outlook.com-263A29?style=for-the-badge&logo=microsoft-outlook&logoColor=blue"
                alt="mailto:matheuscostav@outlook.com" /></a
          ></code>

          <code
            ><a href="https://github.com/MatheusCostaVaz" target="blank"
              ><img
                height="30"
                src="https://img.shields.io/badge/%2FMatheusCostaVaz-263A29?style=for-the-badge&logo=github&logoColor=white"
                alt="https://github.com/MatheusCostaVaz" /></a
          ></code>

          <code
            ><a
              href="https://uniceuma-my.sharepoint.com/:b:/g/personal/matheus92274_ceuma_com_br/EccYw5YDJLxDv6xbu37H4x8BlHRxJOzP44wo_4CPDb8-aA?e=e2eM9s"
              target="blank"
              ><img
                height="30"
                src="https://img.shields.io/badge/CURR%C3%8DCULO-263A29?style=for-the-badge&logo=readdotcv&logoColor=black" /></a
          ></code>
        </p>
      </ul>
    </section>
  </footer>
</template>

<style scoped>
.app__footer {
  display: flex;
  flex-direction: column;
  margin-top: 25px;
  padding: 0.5rem;
  justify-content: space-between;
  align-items: center;
  background: transparent;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.app__footer-sobre,
.app__footer-contatos {
  width: 100%;
  text-align: center;
}

.app__footer-text {
  color: var(--letras);
  font-family: Montserrat;
  font-size: 1.8rem;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
}
</style>
