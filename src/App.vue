<template>
  <div id="app">
    <Kanban :data="data"/>
    
  </div>
</template>

<script>
import Kanban from"./components/Kanban"


export default {
  name: 'App',
  components: {
    Kanban
  },
  data(){
    return{
    data:[
            {
                name:"todu",
                color:"#FF99FF",
            },
            {
                name:"doing",
                color:"#FFFF00",
            },
            {
                name:"done",
                color:"#99FFCC",
            },

        ]
  }
}
        }
</script>

<style>
#app {
  height: 100vh;
}
</style>
