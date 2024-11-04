<template>
  <h1>SmartCook</h1>
  <br /><br />
  <div class="container-btn">
    <button class="btn">Adauga alimente</button>
    <button class="btn">Gateste ceva</button>
    <button class="btn">Retete</button>
    <button class="btn">Alimente aproape de expirare</button>
  </div>
</template>
<style>
div#app {
  margin-left: 450px;
  padding: 0;
}
body {
  margin: 0;
  padding: 0;
  height: 100%;
  background: rgb(0, 212, 255);
  background: linear-gradient(
    90deg,
    rgba(0, 212, 255, 1) 0%,
    rgba(9, 9, 121, 1) 100%,
    rgba(0, 196, 204, 1) 100%
  );
}
.btn {
  text-align: center;
  width: 400px;
  height: 120px;
  font-size: 18px;
  margin: 10px 0;
  background: rgb(255, 102, 196);
  background: linear-gradient(
    90deg,
    rgba(255, 102, 196, 1) 0%,
    rgba(255, 222, 89, 1) 100%
  );
  border: 2px solid;
  border-radius: 50%;
  cursor: pointer;
  transition:
    transform 0.4s,
    box-shadow 0.4s;
}
.btn:hover {
  transform: scale(1.1);
}
.container-btn {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
}
h1 {
  color: #ffbd59;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 50px;
  text-align: center;
}
</style>
