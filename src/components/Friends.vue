<template>
    <div>
        
        <h1>Friends Component</h1>
        <!-- {{ $route.params.id }}
        {{ $route.params.age }}
        {{ $route.params.weight }} -->
        {{ id }}
        {{ age }}
        {{ weight }}
        
    </div>
</template>

<script>


    export default {

        name: "Friends", 
        props: [
            'id',
            'age',
            'weight',
        ],
        components: {
            
        },      
        data(){
            return{
                
            }
        },
        methods: {
            
        }
    }
</script>

<style scoped>
h1{
    color: yellowgreen
}
</style>