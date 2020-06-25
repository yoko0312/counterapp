<template>
  <div class="score">
    <h1>This is a score page</h1>
    <p>{{ count }}</p>
  </div>
</template>
<script>
        export default {
            data() {
                return {
                    
                };
            },
        computed:{
            count(){
                return this.$store.getters.count
                
            }
        }
    };
    </script>