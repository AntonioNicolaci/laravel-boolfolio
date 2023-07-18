<script>
import axios from 'axios';

export default {
    data() {
        return {
            arrWork: [],
        };
    },
    methods: {
        getAPIWork() {
            axios.get('http://localhost:8000/api/works')
                .then(response => console.log(response))
        }
    },
    created() {
        this.getAPIWork();
    },
}
</script>

<template>
  <div>
    ciaio ma 2
  </div>
  
</template>

<style lang="scss">
  
</style>