<template>
    <main>
        <div class="container">
           <div class="text">
               {{textMain}}
           </div>
        </div>
    </main>
</template>

<script>
    export default{

        data() {
            return{
                textMain: "--> Content goes here <--"
            }
        }
    }
    
</script>

<style scoped lang="scss">

    main{
        background-color: rgb(26, 26, 26);
        width: 100%;

    }

    .container{
        width: 1280px;
        display: flex;
        flex-wrap: wrap;
        margin: 0 auto;


        .text{
            margin: 0 auto;
            color: white;
            font-size: 30px;
        }
    }
</style>
