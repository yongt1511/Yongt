<template>
  <div id="app">
    <Header/>
    <list-user/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import ListUser from './components/ListUser.vue'
export default {
  components: { Header, ListUser },
  name: 'app',
  data () {
    return {
      listUser: [
          { id: 1, name:"Hoang Nhat Nam",  email: "test1@gmail.com" , phone: "0369780456" , role: "admin"},
          { id: 2, name:"Hoang Nhat Nam",  email: "test2@gmail.com" , phone: "0369780456" , role: "Nhan vien"},
          { id: 3, name:"Hoang Nhat Nam",  email: "test3@gmail.com" , phone: "0369780456" , role: "Nhan vien"},
          { id: 4, name:"Hoang Nhat Nam",  email: "test4@gmail.com" , phone: "0369780456" , role: "admin"},
          { id: 5, name:"Hoang Nhat Nam",  email: "test5@gmail.com" , phone: "0369780456" , role: "admin"},
          { id: 6, name:"Hoang Nhat Nam",  email: "test6@gmail.com" , phone: "0369780456" , role: "Nhan vien"},
          { id: 7, name:"Hoang Nhat Nam",  email: "test7@gmail.com" , phone: "0369780456" , role: "admin"},
                
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;

}
</style>
