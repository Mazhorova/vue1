<script lang="ts">
export default {
  data() {
    return
  }
}

</script>

<template>
  <div class="wrapper">
    <h1>Приложение погода</h1>
    <p>Узнать погоду</p>
    <input type="text" placeholder="введите город">
    <button>получить погоду</button>
    
  </div>
</template>

<style scoped>
.wrapper {
  width: 900px;
  height: 500px;
  border-radius: 500px;
  background:  rgb(13, 69, 189);
  padding: 20px;
  text-align: center;
  color: white;
  
}
.wrapper h1 {
  margin-top: 50px;

}
.wrapper p {
  margin: 20px;
  font-size: 20px;
}
.wrapper button {
  color: rgb(194, 41, 41);
  font-size: 20px;
  outline: none;
  background: transparent;
  border-radius: 10px;
  padding: 10px 15px;
  margin-left: 20px;
}
.wrapper input {
  margin-top: 30px;
  background: transparent;
  border: 0;
  border-bottom: 2px solid red;
  font-size: 20px;
  padding: 5px 8px;
  outline: none;
}

</style>
