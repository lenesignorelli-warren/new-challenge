<template>
  <div class="columns">
    <div class="column main-column">
        <img alt="destaque1" src="./../assets/img-premios.png" />
    </div>
    <div class="column">
        <h1>Finanças Femininas</h1>
        <br>
        <p>Um guia completo para mulheres realizarem seus sonhos!</p>
        <p>Aprenda a só gastar com o que te faz feliz!</p>
        <br>
        <br>
        <p>Guardar dinheiro todos os meses e multiplicar o que foi poupado com os melhores investimentos!</p>
        <button>Comece Agora</button>
    </div>
</div>
</template>

<script>
export default {
    name: "DestaqueWarren",
}
</script>

<style scoped>
.columns {
  display: flex;
}

img{
  width: 400px;
  height: 500px;
}

.column {
  border: 5px solid #ccc;
  flex: 1;
  padding: 20px;
}

.main-column {
  flex: 2;
  
}

h1 {
  font-size: 30px;
}

p{
    font-size: 20px;
}

button{
    background-color: #e02b57;
    border: none;
}
</style>
