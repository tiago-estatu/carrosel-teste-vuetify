<template>
  
    <v-footer class="pa-3" app>
        <v-spacer></v-spacer>
        <p>{{texto}}</p>
        <v-spacer></v-spacer>
        <div>Vue &copy; {{ new Date().getFullYear() }}</div>
    </v-footer>
 
</template>

<script>
export default {
    data(){
        return{
            texto : 'Teste Vuetify Carrosel'
        }
    }    
}
</script>

<style>

</style>