<template>
  <div>
    <ol>
        <li v-for="p in persons">{{ p }}</li>
    </ol>
  </div>


</template>
<script>
export default {
    data(){
        return{
           persons: ['sajib','karim','rafiq']
        }
    },
   
}
</script>