<template>
    <h1 v-on:mousemove="getConsole()">Home Components{{ 10+10 }}</h1> 

    <h1>Email:{{ email }}</h1>
    <h1>Mobile:{{ mobile}}</h1>
    <h1>Name:{{getName("Sidhu")}}</h1>
    <h1>Name :{{ getName("peter") }}</h1>
    <h1>All Data:{{ getData() }}</h1>
    <button v-on:click="getData('Button 1 Clicked')">Click Me</button>
    <button v-on:dblclick="getData('Button double Clicked')">Click Me</button>
    <h2>{{ count }}</h2>

</template>


<script>
export default {
    name:'HomeScreen',
    data()
    {
        return{
            email:'nil@test.com',
            mobile:9898,
            getName:function(a)
            {
                return a;
            }

        }
    }
    ,
    methods:{
      
        getData()
        {
            return{
                name:'anil',
                email:'anil@sidhu.com'
            }
        },
        getConsole()
        {
            console.warn("function called")
        }

    }


}
</script>
<style scoped>
h1{
    color:orange
    


    

}
</style>