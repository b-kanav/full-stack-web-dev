<script>
    import TodoItem from "$lib/todo-item.svelte";

    const pagetitle =  "todo";
</script>

<svelte:head>
    <title>{pagetitle}</title>
</svelte:head>

<h1>{pagetitle}</h1>

<form action="" method="">
    <input type="text" name="text" aria-label="add a todo" placeholder="+ type to add a todo">
</form>

<TodoItem />
<TodoItem />
<TodoItem />