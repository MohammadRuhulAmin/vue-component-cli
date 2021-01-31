<template>
    <div>
      <CompHeader :myName="name"></CompHeader>
      <CompFooter></CompFooter>
    </div>
</template>

<script>

import CompHeader from './components/Header/Header';
import CompFooter from './components/Footer/Footer';
export default {
  data(){
    return {
      name:"ruhul amin"
    }
  },

  components: {
    CompHeader,CompFooter
  }
}
</script>

<style>

</style>
