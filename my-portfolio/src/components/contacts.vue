<template>
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
</template>

<style scoped>
.container-contact-me{
    height: 15%;
    width: 95%;

    display: flex;
    flex-direction: column;
    justify-content: space-evenly;

    color: white;
}

.container-contact-me h1{
    font-size: 2.5em;
    margin: 0%;
    color: orange;
}

.contact{
    height: 40%;
    width: 100%;

    display: flex;
    align-items: flex-start;
    justify-content: space-evenly;
    flex-direction: column;

    color: orange;
    font-size: 1.2em;
}
</style>