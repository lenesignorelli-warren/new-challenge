<template>
  <div class="destaque">
    <div class="mulher1">
        <img alt="mulheres" src="./../assets/img-premios.png" />
    </div>
    <div class="mulher2">
        <h1>Finanças Femininas</h1>
        <p>Um guia completo para mulheres realizarem seus sonhos!</p>
        <p>Aprenda a só gastar com o que te faz feliz!</p>
        <p>Guardar dinheiro todos os meses e multiplicar o que foi poupado com os melhores investimentos!</p>
        <button>Comece Agora</button>
    </div>
</div>
</template>

<script>
export default {
    name: "DestaqueWarren"
}
</script>

<style scoped>
.destaque {
  display: flex;
  justify-content: space-evenly;
}

img {
  width:500px;
}

.mulher1, .mulher2 {
  border: 2px solid black;
}

.mulher2{
  width: 500px;
}

h1 {
  font-size:50px;
}

p{
    font-size: 20px;
}

button {
    background-color: #e02b57;
    border: none;
}
</style>
