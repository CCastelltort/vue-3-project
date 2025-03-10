<template>
    <div>
        <header></header>
        <!--We want header content here-->
        <slot name="header"></slot>
    
        <main></main> 
        <!--We want main content here-->
        <slot name="main"></slot>

        <footer></footer>
        <!--We want footer content here-->
        <slot name="footer"></slot>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>