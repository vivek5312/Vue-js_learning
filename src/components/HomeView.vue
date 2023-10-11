<template>
  <h1>Email {{ email }}</h1>
  
  <h1>Name: {{ getname("vivek") }}</h1>
  <h1> Data: {{getData()}}</h1>
</template>

<script>
export default {
  name: "HomeView",
  data() {
    return {
      email: "vivek@gmail.com",
    };
  },
  methods:{
    getname(name){
        return name
    },
    getData(){
        return {
            name:'vivek',
            age:22,
            email:this.email
        }
    }
  }
};
</script>

<style scoped>
h1 {
  color: orange;
}
</style>
