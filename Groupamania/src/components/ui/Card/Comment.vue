<script>
import Avatar from "../Avatar.vue"
export default {
    name:"Comment",
    components : {
        Avatar
    }
}

</script>

<template>

<div class="d-flex gap-1">
    <Avatar />
 <div class="d-flex flex-column comment_text p-1">  
    <p>Sylvie du Marketing</p>
    <p>that's great!!</p>
</div> 
</div>
</template>

<style scoped>
.comment_text{
    background-color: var(--bs-gray-200);
    border-radius: 5px;
    width: 100%;
   
}

.card-body > .d-flex {
    margin-bottom: 1em;
   
}


img {
    margin:0
}
.d-flex p{
    margin-bottom: 0;
}
.d-flex p:nth-child(1) {
    font-weight:bold;
}
</style>