<script setup>
import { ref } from 'vue'
</script>

<template>
  <header class="barragamer">

    <div class="questaobala">
      <h2 class="numero">1°</h2>
    </div>

    <div class="materia">
      <h2 class="fodao">FutQuiz</h2>
    </div>
  </header>

  <main>
    <div class="container">

      <div class="question">
        <div class="pergunta">
          <h1>Qual jogador foi eleito o melhor do mundo em 2021 pela FIFA?</h1>
        </div>

        <div class="img">
        </div>
        <!-- Fim de Questao -->
      </div>

      <div class="respostas">
        <button type="button" class="resposta1">Cristiano Ronaldo</button>
        <button type="button" class="resposta2">Lionel Messi</button>
        <button type="button" class="resposta3">Robert Lewandowski</button>
        <button type="button" class="resposta4">Kylian Mbappe</button>
      </div>

      <!-- Fim do container -->
    </div>
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bruno+Ace&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Ysabeau+SC:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap');

.resposta1 {
  color: white;
  background-color: rgba(232, 66, 252, 255);
  padding: 5px 5px;
  margin: 10px 10px 10px 10px;
  cursor: pointer;
  font-family: 'Ysabeau SC', sans-serif;
  border-color: rgba(3, 164, 255, 255);
  border-style: groove;
  font-size: 30px;
  text-align: center;
  align-items: center;
}
.resposta2 {
  color: white;
  background-color: rgba(3, 164, 255, 255);
  padding: 5px 5px;
  margin: 10px 10px 10px 10px;
  cursor: pointer;
  font-family: 'Ysabeau SC', sans-serif;
  border-color: rgba(232, 66, 252, 255);
  border-style: groove;
  font-size: 30px;
  text-decoration: none;
}
.resposta3 {
  color: white;
  background-color: rgba(232, 66, 252, 255);
  padding: 5px 5px;
  margin: 10px 10px 10px 10px;
  cursor: pointer;
  font-family: 'Ysabeau SC', sans-serif;
  border-color: rgba(3, 164, 255, 255);
  border-style: groove;
  font-size: 30px;
  text-decoration: none;
}
.resposta4 {
  color: white;
  background-color: rgba(3, 164, 255, 255);
  padding: 5px 5px;
  margin: 10px 10px 10px 10px;
  cursor: pointer;
  font-family: 'Ysabeau SC', sans-serif;
  border-color: rgba(232, 66, 252, 255);
  border-style: groove;
  font-size: 30px;
  text-decoration: none;
}
.barragamer {
  text-align: center;
  font-size: 50px;
  border-style: groove;
  border-width: 10px;
  background-color: rgba(3, 164, 255, 255);
  border-color: rgba(232, 66, 252, 255);
}

.tema {
  background-color: rgb(0, 0, 0);
  padding: 20px 30px;
  color: rgb(183, 210, 219);
  border-radius: 10px;
  text-align: center;
  display: flex;
  flex-direction: column;
  width: 26%;
  margin: 0 auto;
  margin-top: 8%;
  margin-bottom: 20px;
  border-style: groove;
  box-shadow: 8px 8px 8px black;
}

.questaobala {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 2%;
}

.pergunta {
    margin-top: 40px;
    margin-bottom: 20px;
    text-align: center;
    align-items: center;
    color: rgb(0, 0, 0);
    font-family: 'Bruno Ace', cursive;
    font-size: 50px;

}
</style>
