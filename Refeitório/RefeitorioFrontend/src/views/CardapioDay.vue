<script></script>
<template>
  <div class="semana">
    <h1>Segunda-feira</h1>
    <span>24/02/2006</span>
    <div class="setas">
      <img src="@/img/setaEsquerda.png" alt="" />
      <img src="@/img/setaDireita.png" alt="" />
    </div>
  </div>
  <div class="comidas">
      <span class="prato">Prato Principal</span>
      <span class="nomecomida">STROGONOFF DE CARNE</span>
      <hr />
      <div class="separador"></div>
      <img class="tabela" src="@/img/tabela.png" alt="" />
      <span class="infonutri">Informação nutricional</span>

    <img class="imgcomida" src="@/img/01.png" alt="">
  </div>
  <!-- <div class="comidas1">
      <span class="prato">Opção de Proteína</span>
      <span class="nomecomida">SOJA REFOGADA</span>
      <hr>
      <img class="tabela" src="@/img/tabela.png" alt="" />
      <span class="infonutri">Informação nutricional</span>
    </div>
    <div class="comidas2">
      <span class="prato">Acompanhamento</span>
      <span class="nomecomida">QUIBEBE, ARROZ, ARROZ INTEGRAL, FEIJÃO</span>
      <hr>
      <img class="tabela" src="@/img/tabela.png" alt="" />
      <span class="infonutri">Informação nutricional</span>
    </div>
    <div class="comidas3">
      <span class="prato">Saladas</span>
      <span class="nomecomida">TABULE, BETERRABA RALADA, CHICÓRIA  </span>
      <hr>
      <img class="tabela" src="@/img/tabela.png" alt="" />
      <span class="infonutri">Informação nutricional</span>
    </div>
    <div class="comidas4">
      <span class="prato">Sobremesa</span>
      <span class="nomecomida">GELATINA</span>
      <hr>
      <img class="tabela" src="@/img/tabela.png" alt="" />
      <span class="infonutri">Informação nutricional</span>
    </div> -->
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Birthstone&display=swap");

.infos {
  margin-left: 10%;
}
.semana {
  position: absolute;
  width: calc(100% - 20px);
  height: 70px;
  left: 20px;
  top: 200px;
  background: #49784d;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 20px 0px 0px 20px;
}
.semana h1 {
  color: white;
  font-family: inter;
  font-size: 20px;
  display: flex;
  justify-content: center;
}
.semana span {
  color: white;
  font-family: inter;
  font-weight: 400;
  font-size: 14px;
  display: flex;
  justify-content: center;
  margin: -12px 0 0 0;
}
.setas {
  display: flex;
  justify-content: space-between;
  width: 60%;
  left: 20%;
  top: 27px;
  position: absolute;
}
.setas img {
  width: 15px;
}
.comidas {
  background-color: white;
  width: calc(90% + 3%);
  height: 110px;
  position: absolute;
  top: 320px;
  border-radius: 10px;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  display: flex;
  margin-left: 1%;
  flex-direction: column;
  align-items: center;
}
.prato {
  font-family: "Birthstone";
  font-style: normal;
  font-weight: 400;
  font-size: 30px;
  line-height: 41px;
  margin-left: 80px;
  text-align: center;
  color: #000000;

  mix-blend-mode: normal;
}

.nomecomida {
  color: #49784d;
  margin-left: 80px;
  font-family: "Inter";
  font-weight: 500;
  font-size: 11px;
}

.tabela {
  width: 24px;
  margin-left: 80px;
  margin-top: 3%;
  padding: 0;
}

.comidas hr {
  width: 40%;
  margin-left: 165px;
  height: 1px;
  /* padding: 0;
  margin: 0; */
}
.separador {
width: 110px;
height: 0px;
margin-top: -20px;
margin-right: 50%;
border: 0.7px solid #2020206b;
transform: rotate(-90deg);
}

.infonutri {
  font-size: 10px;
  margin-left: 80px;
}
.imgcomida {
  margin-right: 75%;
  
  margin-top: -75px;
}
/* .comidas1{
    background-color: white;
      width: calc(90% + 3%);
      height: 110px;
      position: absolute;
      top: 450px;
      border-radius: 10px;
      box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
      display: flex;
      margin-left: 1%;
      flex-direction: column;
      align-items: center;
}

.comidas2{
    background-color: white;
      width: calc(90% + 3%);
      height: 110px;
      position: absolute;
      top: 580px;
      border-radius: 10px;
      box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
      display: flex;
      margin-left: 1%;
      flex-direction: column;
      align-items: center;
}
.comidas3{
    background-color: white;
      width: calc(90% + 3%);
      height: 110px;
      position: absolute;
      top: 710px;
      border-radius: 10px;
      box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
      display: flex;
      margin-left: 1%;
      flex-direction: column;
      align-items: center;
}
.comidas4{
    background-color: white;
      width: calc(90% + 3%);
      height: 110px;
      position: absolute;
      top: 840px;
      border-radius: 10px;
      box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
      display: flex;
      margin-left: 1%;
      flex-direction: column;
      align-items: center;
}


.comidas1 hr {
    width: 40%;
      height: 1px;
      padding: 0;
      margin: 0;
}
.comidas2 hr {
    width: 40%;
      height: 1px;
      padding: 0;
      margin: 0;
}
.comidas3 hr {
    width: 40%;
      height: 1px;
      padding: 0;
      margin: 0;
}
.comidas4 hr {
    width: 40%;
      height: 1px;
      padding: 0;
      margin: 0;
} */
</style>
