<template>
  <div>
    <h1 class="text-3xl font-bold text-red-400 underline"> Steel-Castles Api is working!</h1>
    <img src="https://tech.osteel.me/images/2020/03/04/hello.gif" alt="Hello there" className="center">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloThere',
  props: {
    msg: String
  }
}
</script>

<style>
p {
  font-family: "Arial", sans-serif;
  font-size: 90px;
  text-align: center;
  font-weight: bold;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
</style>
