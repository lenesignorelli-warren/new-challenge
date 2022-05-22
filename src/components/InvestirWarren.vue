<template>
  <section class="container">
      <div class="investir">
          <h1>Investir é sobre você</h1>
          <p>COMECE A INVESTIR EM POUCOS MINUTOS. DESCOMPLIQUE.</p>
      </div>
      <div class="button">
          <button>Comece Agora</button>
      </div>
  </section>
</template>

<script>
export default {
  name: "InvestirWarren"
};
</script>

<style>
.container {
    background-color: #cdcaca;
    display: flex;
    justify-content: space-evenly;
    padding: 50px;
    color: white;
}

.button {
    display: flex;
}

.investir, .button {
    border: 1px solid red;
}

h1 {
  font-size:50px;
}

p {
  font-size: 20px;
}
</style>