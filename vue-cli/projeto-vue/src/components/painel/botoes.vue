<template>
    <div id='componente'>

        <input type="button" value="+">
        <input type="button" value="-">
        <input type="button" value="*">

        <input type="button" value="7">
        <input type="button" value="8">
        <input type="button" value="9">
        

        <input type="button" value="4">
        <input type="button" value="5">
        <input type="button" value="6">

        <input type="button" value="1">
        <input type="button" value="2">
        <input type="button" value="3">
       

        <input type="button" value="0">
        <input type="button" value=".">
        <input type="button" value="=">
    </div>
</template>

<script>
export default {
    name: 'Botoes'
}
</script>

<style scoped>
    #componente{
        width: 400px;
        
        margin:0 auto;

    }

    div>input{
        margin: 1px;
        padding: 5px;
        width: 130px
    }

</style>