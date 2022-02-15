<style>
  .todo {
        display: grid;
		grid-template-columns: 2rem 1fr 2rem;
		grid-gap: 0.5rem;
		align-items: center;
		margin: 0 0 0.5rem 0;
		padding: 0.5rem;
		background-color: white;
		border-radius: 8px;
		filter: drop-shadow(2px 4px 6px rgba(0, 0, 0, 0.1));
		transform: translate(-1px, -1px);
		transition: filter 0.2s, transform 0.2s;
  }

  .todo button {
		width: 2em;
		height: 2em;
		border: none;
		background-color: transparent;
		background-position: 50% 50%;
		background-repeat: no-repeat;
  }

  .todo input {
    flex: 1;
		padding: 0.5em 2em 0.5em 0.8em;
		border-radius: 3px;
  }

  button.toggle {
    border: 1px solid rgba(0, 0, 0, 0.2);
		border-radius: 50%;
		box-sizing: border-box;
		background-size: 1em auto;
  }

  .text {
		position: relative;
		display: flex;
		align-items: center;
		flex: 1;
  }


</style>

<div class="todo">
    <form action="" method="">
        <input type="hidden" name="done" value="">
        <button aria-label="Mark done / not done" class="toggle">Done/Not Done</button>
    </form>

    <form action="" method="" class="text">
        <input type="text" value="">
        <button aria-label="Save ToDo" class="save">Save</button>
    </form>

    <form action="" method="">
        <button aria-label="Delete ToDo" class="delete">Delete</button>
    </form>

</div>