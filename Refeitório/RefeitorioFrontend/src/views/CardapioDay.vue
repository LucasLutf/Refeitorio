<script></script>
<template>
  <div class="semana">
    <h1>Segunda-feira</h1>
    <span>24/02/2006</span>
    <div>
      <img class="direita" src="@/img/image24.png" alt="" />
      <img class="esquerda" src="@/img/image15.png" alt="" />
    </div>
  </div>
</template>

<style>
.semana {
  position: absolute;
  width: 408px;
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
.direita img {
  display: flex;
}
</style>
