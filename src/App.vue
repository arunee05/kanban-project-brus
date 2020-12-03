<template>
  <div id="app">
  <Kanban :data="data"/>
    </div>
</template>

<script>
import Kanban from "./components/Kanban"

export default {
name:"App",
  components: { 
    Kanban 
    },
    data(){
      return{
        data:[
          {
            name:"todo",
            color:"#B269E7",
            tasks:[]
          },
          {
            name:"todo",
            color:"#69A7E7",
            tasks:[] 
          },
          {
            name:"todo",
            color:"#E769D1 ",
            tasks:[] 
          }
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
