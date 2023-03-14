<script setup lang="ts">



</script>


<template>
    <!-- Make this toolbar draggable -->
    <div id="toolbar" class="toolbar">
        <span class="tools">X</span>
        <span class="tools">X</span>
        <span class="tools">X</span>
    </div>
</template>



<style lang="scss" scoped>
    .toolbar {
        display: flex;
        align-items: center;
        position: relative;
        justify-content: space-evenly;
        border-radius: 50px;
        top: 2vw;
        background-color: #F3E5AB;
        width: 18vw;
        height: 30px;
        cursor: move;

        
    };

    .tools {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        cursor: pointer;
    };
    

</style>