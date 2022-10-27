<template>
  <div class="main">
    <div class="content">
      <div class="brand">
        <img src="@/img/logoifc.png" alt="logo_ifc" />
      </div>
      <div class="infos">
        <h2>Refeitório</h2>
        <hr />
        <h3>Cardapio da semana</h3>
      </div>
      <div class="icon">
        <img src="@/img/tresrisco.png" alt="" />
      </div>
    </div>
  </div>
</template>
<style>
.main {
  position: absolute;
  width: 100%;
  height: 233px;
  top: 0;
  left: 0%;

  background: linear-gradient(180deg, #468741 0%, rgba(217, 217, 217, 0) 100%);
}
.content {
  position: absolute;
  width: calc(100% - 20px);
  height: 130px;
  left: 20px;
  top: 24px;

  background: #49784d;
  mix-blend-mode: normal;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 30px 0px 0px 24px;
}
.brand {
  position: absolute;
  width: 85px;
  height: 85px;
  top: 26px;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  left: 5%;
}
.infos {
  align-items: center;
  text-align: center; color: #ffffff;

  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.infos h2 {
  font-family: "Inter";
  font-style: normal;
  font-weight: 900;
  font-size: 28px;
  margin-bottom: 0;
}
.infos hr {
  width: 50%;
  top: 40px;
  border: 1px solid rgba(255, 255, 255, 0.6);
}
.infos h3 {
  top: 50px;
  font-family: "Inter";
  font-style: normal;
  font-weight: 400;
  font-size: 17px;
  line-height: 21px;
  justify-content: center;
  display: flex;
  align-items: center;
  text-align: center;

  color: #ffffff;
}
.icon {
  position: absolute;
  width: 21.29px;
  height: 15.68px;
  top: 24%;
  left: 85%;
}

</style>
