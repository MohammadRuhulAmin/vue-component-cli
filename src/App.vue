<template>
    <div>
      <CompHeader
       :firstName="fName"
        :lastName="lName"
        :age="age"
      >

      </CompHeader>
      <CompFooter></CompFooter>
    </div>
</template>

<script>

import CompHeader from './components/Header/Header';
import CompFooter from './components/Footer/Footer';
export default {
  data(){
    return{
      fName:"John",
      lName:"doe",
      age:55,
    }

  },

  components: {
    CompHeader,CompFooter
  }
}
</script>

<style>

</style>
