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
        <profile />
        <div class="container-information">
          <aboutme />
          <projects />
          <tools />
          <contacts />
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
  import profile from './components/profile.vue';
  import aboutme from './components/aboutme.vue';
  import contacts from './components/contacts.vue';
  import tools from './components/tools.vue';
  import projects from './components/projects.vue';

  export default {

    components: {
      profile,
      aboutme,
      projects,
      contacts,
      tools
    }
  }
</script>

<style src="/public/css/app.css"></style>