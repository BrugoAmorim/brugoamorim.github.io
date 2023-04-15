<template>
    <div class="container-profile">
        <div class="container-info">
        <div class="img-profile">
            <img src="/image/profile.jpg" height="93%" alt="my profile picture">
            <span>Bruno Gomes de Amorim Silva</span>
        </div>
        <div class="links">
            <a href="https://www.linkedin.com/in/bruno-gomes-a9b769244/" target="_blank" style="background-color: #1CC8FF;">Siga-me no Linkedin</a>
            <a href="https://twitter.com/BrugoAmorim" target="_blank" style="background-color: #2F9BFF;">Siga-me no Twitter</a>
            <a href="https://github.com/BrugoAmorim" target="_blank" style="background-color: black;">Siga-me no Github</a>
        </div>
        </div>
    </div>
</template>

<style scoped>
.container-profile{
    height: 100%;
    width: 35%;

    display: flex;
    align-items: flex-start;
    justify-content: center;
}

.container-info{
    height: 75%;
    width: 25%;

    margin-top: 1.3%;
    border: 8px solid orange;

    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-evenly;

    background-color: #5F3AC9;
    position: fixed;
}

.img-profile{
    height: 55%;
    width: 80%;

    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-evenly;

    color: white;
}

.img-profile img{
    border-radius: 5%;
}

.links{
    height: 35%;
    width: 85%;

    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}

.links a{
    height: 25%;
    margin: 1%;

    border: none;
    outline: none;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;

    color: white;
    font-size: 90%;
    font-family: Arial, Helvetica, sans-serif;
}

.links a:hover{
    background-image: linear-gradient(rgb(0 0 0/40%) 0 0);
}
</style>