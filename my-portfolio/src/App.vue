<template>
  <div class="body">
    <div class="container-master">
      <header>
        <div class="container-hashtag">@BrugoAmorim</div>
        <div class="container-links">
          <a href="https://twitter.com/BrugoAmorim" target="_blank"> 
            <img src="./assets/twitter.svg" alt="logo twitter" height="40em"/>
          </a>
          <a href="https://github.com/BrugoAmorim" target="_blank">
            <img src="./assets/github.svg" alt="logo github" height="40em"/>
          </a>
          <a href="https://www.linkedin.com/in/bruno-gomes-a9b769244/" target="_blank">
            <img src="./assets/linkedin.svg" alt="logo linkedin" height="40em"/>
          </a>
        </div>
      </header>
      <article>
        <div class="container-profile">
          <div class="container-info">
            <div class="img-profile">
              <img src="/image/profile.jpg" height="90%" alt="my profile picture">
              <span>Bruno Gomes de Amorim Silva</span>
            </div>
            <div class="links">
              <a href="https://www.linkedin.com/in/bruno-gomes-a9b769244/" target="_blank" style="background-color: #1CC8FF;">Siga-me no Linkedin</a>
              <a href="https://twitter.com/BrugoAmorim" target="_blank" style="background-color: #2F9BFF;">Siga-me no Twitter</a>
              <a href="https://github.com/BrugoAmorim" target="_blank" style="background-color: black;">Siga-me no Github</a>
            </div>
          </div>
        </div>
        <div class="container-information">
          <div class="container-about-me">
            <h1>Sobre mim</h1>
            <p>Olá, me chamo Bruno e sou um desenvolvedor web.</p>
            <p>
              Estou nessa área a pouco mais de dois anos, comecei em 2020 fazendo um curso técnico que me deu a base de muitas coisas que sei hoje, mas ao longo do tempo venho me especializando, fazendo outros cursos e estudando por conta própria.
            </p>
            <p>
              Durante esse tempo de especialização eu percebi que eu tenho uma enorme facilidade com desenvolvimento de API’s, no caso, eu sou mais pro lado do desenvolvimento backend, mas também tenho um grande interesse por design e desenvolvimento frontend, em geral, atuando grande parte do tempo como full-stack.
            </p>
          </div>
          <div class="container-projects">
            <div class="title">
              <h1>Projetos principais</h1>
            </div> 
            <div class="projects">
              <div class="work">
                <div class="img-home">
                  <img src="/image/home-agenda-pessoal.png" height="100%" width="100%" alt="imagem home agenda pessoal">
                </div>
                <div class="info-project">
                  <div class="title-work">
                    <h2>Agenda Pessoal</h2>
                  </div>
                  <div class="desc-work">
                    <p>Aplicação web que ajuda os usuários a organizar a sua rotina, fazendo anotações, gerenciando contatos e criando listas de afazeres.</p>
                  </div>
                  <div class="link">
                    <a href="https://github.com/BrugoAmorim/Agenda-Pessoal" target="_blank" class="btn btn-dark">Github</a>
                  </div>
                </div>
              </div>
              <div class="work-2">
                <div class="img-home">
                  <img src="/image/home-test-drive.png" height="100%" width="100%" alt="imagem home agenda pessoal">
                </div>
                <div class="info-project">
                  <div class="title-work">
                    <h2>Test drive</h2>
                  </div>
                  <div class="desc-work">
                    <p>Sistema web de uma concessionária que agenda test drive para os clientes experimentarem os automóveis da loja.</p>
                  </div>
                  <div class="link">
                    <a href="https://github.com/BrugoAmorim/Sistema-Test-Drive" target="_blank" class="btn btn-dark">Github</a>
                  </div>
                </div>
              </div>

            </div>
          </div>
          <div class="container-tools">
            <h1>Ferramentas usadas</h1>
            <div class="tools-1">
              <span style="min-width: 18%;">MySql</span>
              <span style="margin-left: 3%; min-width: 22%;">MongoDb</span>
            </div>
            <div class="tools-2">
              <span style="min-width: 11%;">C#</span>
              <span style="margin-left: 3%; min-width: 17%;">HTML</span>
              <span style="margin-left: 3%; min-width: 14%;">CSS</span>
              <span style="margin-left: 3%; min-width: 23%;">Javascript</span>
            </div>
            <div class="tools-3">
              <span style="min-width: 17%;">NodeJs</span>
              <span style="margin-left: 3%; min-width: 14%;">MVC</span>
              <span style="margin-left: 3%; min-width: 15%;">.NET</span>
              <span style="margin-left: 3%; min-width: 17%;">Github</span>
            </div>
          </div>
          <div class="container-contact-me">
            <h1>Formas de contato</h1>
            <p>
              Se estiver precisando de mais um para fazer parte do seu time, ou, precisar de alguém para tornar a sua aplicação real, entre em contato comigo para colocarmos a mão na massa!
            </p>
            <div class="contact">
              <span>+55 11 95137-7351</span>
              <span>brunogomes.concomercial@gmail.com</span>
            </div>
          </div>
        </div>
      </article>
      <footer>
        <div class="container-credits">
          <p>
            Todo o código desse portifólio se encontra no <a href="https://github.com/BrugoAmorim/my-portfolio" target="_blank">Github</a>. @BrugoAmorim 2023
          </p>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
  import 'bootstrap/dist/css/bootstrap.css';

  export default {

    data() {
      return {
      }
    }
  }
</script>

<style src="/public/css/app.css"></style>