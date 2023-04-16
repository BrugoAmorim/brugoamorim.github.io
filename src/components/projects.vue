<template>
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
</template>

<style scoped>
.container-projects{
    height: 35%;
    width: 95%;

    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.title{
    height: 10%;
    color: orange;
}

.projects{
    height: 90%;

    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: wrap;

    justify-content: flex-start;
}

.work, .work-2{
    width: 43%;
    height: 95%;
    min-height: 95%;
    margin-left: 2%;
}

.img-home{
    height: 45%;
    width: 100%;

    display: flex;
    align-items: center;
    justify-content: center;

    border-top-right-radius: 4px;
    border-top-left-radius: 4px;

    border: 2px solid orange;
    background-color: orange;
}

.img-home img{
    border-top-right-radius: 4px;
    border-top-left-radius: 4px;
}

.info-project{
    height: 55%;
    width: 100%;
    background-color: orange;

    display: flex;
    flex-direction: column;

    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px;
}

.info-project p{
    margin: 0%;
}

.title-work{
    height: 20%;
    padding: 2%;

    align-items: center;
    color: black;
}

.desc-work{
    height: 50%;
    padding: 2%;

    align-items: center;
    color: white;
}

.link{
    flex-grow: 1;

    display: flex;
    align-items: center;
    flex-direction: row;
}

.link :is(a, button){
    margin-left: 2%;
}
</style>