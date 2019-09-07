<template>
  <div class="calculator">
    <div class="display"> 07.78641</div>
      <div class = 'btn'>C</div>
      <div class = 'btn'>+/-</div>
      <div class = 'btn'>%</div>
      <div class = 'btn operator'>÷</div>

      <div class = 'btn'>7</div>
      <div class = 'btn'>8</div>
      <div class = 'btn'>9</div>
      <div class = 'btn operator '>*</div>

      
      <div class = 'btn'>4</div>
      <div class = 'btn'>5</div>
      <div class = 'btn'>6</div>
      <div class = 'btn operator'>x</div>

      <div class = 'btn'>1</div>
      <div class = 'btn'>2</div>
      <div class = 'btn'>3</div>
      <div class = 'btn operator'>+</div>

      <div class= "zero btn ">0</div>
      <div class = 'btn'>.</div>
      <div class = 'btn operator'>=</div>

  </div>
   
</template>

<script>
export default {

}
</script>

<style scoped>

.calculator{
  margin : 0 auto;
  width:300px;
  display: grid;
  justify-content: center;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
  font-size: 20px;
  text-align: center;

}
.display{
  font-size:30px;
  grid-column: 1 / 5;
  background-color: pink;
  color:azure;

}
.zero{
   grid-column: 1/3;
}
.btn{
  background-color: blanchedalmond;
  border: .5px solid #333;
}
.operator{
  background-color: orange;
  color: white;
}
</style>
