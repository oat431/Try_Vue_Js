<template>
    <td>{{name}}</td>
    <td>{{age}}</td>
</template>

<script>
export default {
   props:{
       name : String,
       age : Number
   }
}
</script>