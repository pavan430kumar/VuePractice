<template>
    <div>
        <h1> {{Message}} </h1>
        <app-input :msg="Message" @changed:msg="val => Message = val"></app-input>
    </div>
</template>

<script>
import Input from './Input.vue'
export default {
    data(){
        return{
            Message : 'This is message-P vue!'
        }
    },
  components:{
     'app-input':Input
  }
}
</script>









