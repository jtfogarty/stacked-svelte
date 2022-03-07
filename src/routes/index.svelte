<script>
import TodoItem from "$lib/todo-item.svelte";
const title = "ToDos";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<form action="" method="">
  <input type="text"  name="text" aria-label="Add a ToDo" placeholder="+ type to add a todo" /> 
</form>
<TodoItem />