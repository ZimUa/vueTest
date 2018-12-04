<template>
    <div class="container">
      <form>
        <input v-for="(name, i) in fields" :type="name" :key="i">
        <hr>
      </form>
    </div>
</template>

<script>
export default{
    name: 'Forms',
    data(){
        return{
           
        }
    },
    props:['fields']
}
</script>

<style scoped>
.container{
  width: 50%;
  margin: auto;
  padding: 5px 0px 5px 0px;
  background-color:rgb(89, 205, 209);
  box-shadow: 1px 2px 2px grey;
}
</style>
