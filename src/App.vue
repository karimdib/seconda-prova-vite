<script >
export default{
  data(){
    return{
      message:'ciao come stai?'
    }
  }
}

</script>

<template>
  <div>
    <div class="messaggio">{{ message }}</div>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style >
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.messaggio{
  color: greenyellow;
}
</style>
