<template>
    <div class='display'>
        <textarea class='display' disabled readonly v-model='teste' ></textarea>
    </div>
</template>

<script>
export default {
    data(){
        return{
        teste:'olá calc'
    }
    },
    name:  'Display',
    props:{valores:[]}
}



</script>

<style scoped>
    textarea{
        margin: 0 auto ;
        width: 400px;
        height: 50px;
        resize: none
    }
    #display{
        margin: 0 auto ;
        width: 400px;
        height: 50px;
        resize: none
    }
</style>