<template>
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
</template>

<style scoped>
.container-tools{
    height: 20%;
    width: 95%;
    
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}

.container-tools h1{
    margin: 0%;
    font-size: 2.5em;
    color: orange;
}

.tools-1, .tools-2, .tools-3{
    height: 25%;
    width: 100%;

    display: flex;
    flex-direction: row;
    align-items: center;
}

.tools-1 span, .tools-2 span, .tools-3 span{
    padding: 0.6%;
    cursor: pointer;

    display: flex;
    align-items: center;
    justify-content: center;
    
    color: white;
    font-size: 1.7em;
    border-radius: 6px;
    background-color: orange;
}

.container-tools span:hover{
    transition: 0.2s;
    background-color: rgb(221, 144, 1);
}

.container-tools span:active{
    transition: 0.3s;
    background-color: rgb(192, 125, 0);
}
</style>