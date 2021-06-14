<template>
  <div class="list-user">
    <user/>
      <p>list-User</p>
  </div>
</template>

<script>
import User from './User.vue'
export default {
  components: { User },
name : 'list-user',
props:{
  listUser:{
    type: Array,
    default:[],
  },
},
data(){
    return{

    }
}
}
</script>

<style>

</style>