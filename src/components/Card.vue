<template>
<ol>
    <li v-for="student in students" :key="student">Name: {{ student.name }} - Age: {{ student.age }}</li>
</ol>
</template>
<script>
export default {
    data(){
        return{
            students: [
                {name: 'sajib',age: 23},
                {name: 'Rafiq',age: 26},
                {name: 'Karim',age: 25}
            
            
            ]
        }
    }
}
</script>