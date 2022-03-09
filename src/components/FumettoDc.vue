<template>
   <div class="box_fumetto">
       <img :src="thumb" alt="">
       <h4 class="titolo_fumetto">{{series}}</h4>
   </div>
</template>

<script>
export default{
    props: ["thumb","series"]
}
</script>


<style lang="scss" scoped>
    img{
        width: 100%
    }

    .box_fumetto{
        width: 180px;
        .titolo_fumetto{
            color: white;
            text-transform: uppercase;
        }
        
    }
</style>