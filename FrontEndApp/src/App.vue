<script setup>

</script>

<template>
  <div class="row">
    <div class="function">
      <p>Here goes the function</p>
    </div>
    
    <div class="column">
      <div class="graph">
        <p>Here goes the graph</p>
      </div>
      <div class="equ">
        <p>Here goes the equation</p>
      </div>
    </div>
  </div>

  <div class="data">
    <p style="color: #000;">Here goes the data</p>
  </div>
</template>

<style scoped>
.row {
  width: 100%;
  height: 682px;
  display: flex;
  flex-direction: row;
}

.column {
  height: 100%;
  width: 850px;
}
.function {
  background-color: red;
  height: 100%;
  width: 350px;
  display: flex;
  flex-direction: column;
}
.graph {
  background-color: blue;
  width: 100%;
  height: 70%;
  display: flex;
}
.equ {
  background-color: green;
  display: flex;
  width: 100%;
  height: 30%;
}
.data {
  background-color: yellow;
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 40px;
}
</style>
