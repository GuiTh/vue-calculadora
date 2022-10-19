<template>
  <div class="calculator">
    <Display />
    <Button />
  </div>
</template>

<script>
import Display from "../components/Display"
import Button from "../components/Button"
export default {
    components:{Button,Display}
}
</script>

<style>
.calculator{
    height: 320px;
    width:235px ;
    
}
</style>