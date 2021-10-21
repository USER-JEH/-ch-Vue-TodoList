<template>
  <div class="todo-header">
      <input type="text" placeholder="Add your todo list,push Enter key to compulite">
  </div>
</template>

<script>
export default {
    name:'MyHeader'
}
</script>

<style scoped>
.todo-header input{
    width: 97%;
    height: 28px;
    font-size: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 4px 7px;
}

.todo-header input:focus {
    outline: none;
    border-color: rgba(82, 168, 236, 0.8);
    box-shadow: inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(82, 168, 236, 0.6)
}
</style>