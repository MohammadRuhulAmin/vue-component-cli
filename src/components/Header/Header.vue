<template>
    <div>
        <p>First Name:{{firstName}}</p>
        <p>Last Name:{{lastName}}</p>
        <p>Age:{{age}}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
    export default{
        props:{
            firstName:String,
            lastName:String,
            age:Number
        },

        methods:{
            updateName(){
                this.firstName="Ruhul";
                this.lastName = "Amin";
                this.age = 25;
            }
        }
    }
</script>

<style>



</style>