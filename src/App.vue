<template>
 <div id= "app">

<main>
<div class = "search-box">
  <input type="text" class="search-bar" placeholder="Search..."/>
</div>

  </main>

   </div>
</template>

<script>


export default {
  name: 'app',

  data(){
    return {
      api_key :'8f26ab2cdfa6697e601a01e9a64dc38c '
    }

  }

 
  
}
</script>

<style>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
  body{
    font-family: 'montserrat',sans-serif;
  }

#app{
  background-image:url('./assets/cold-bg.jpg');
  background-size:cover;
  background-position:bottom;
  transition:0.4s;
}

main{
  min-height:100vh;
  padding:25px;
  background-image:linear-gradient(to bottom, rgba(0,0,0,0), rgba(0,0,0,.75));
}

.search-box{
  width: 100%;
  margin-bottom:30px;
}

</style>
