<script>
import Card from "../../components/ui/Card/Card.vue";
export default{
    name: "PostForm",
    components: { Card }
}
</script>


<template>

<div class="form-floating mt-4">
  <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
  <label for="floatingTextarea">Comments</label>
</div>

<div class="d-flex">
<label for="file-input" class="btn btn-secondary mt-1">Add image</label>
<input id="file-input" type="file" />
<button type ="button" class="btn btn-primary mt-1 ms-auto">Post</button>
</div>
<hr class="dropdown-divider mt-4" />
<Card></Card>
<Card></Card>
<Card></Card>


</template>


<style module>
input{
    display: none;
}

body{
    background-color: #807b7b1a !important;
}
</style>