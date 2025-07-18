<script lang="ts">
  import "bootstrap/dist/css/bootstrap.css";
  import TodoCard from "./components/TodoCard.svelte";
</script>

<main>
  <div class="todo-cards-container">
    <TodoCard
      onStart={(id:number) => console.log(`Start ${id}`)}
      id={1}
      title="Learn Svelte"
      description="Understand the basics of Svelte and its reactivity model."
    />
    <TodoCard
    onStart={(id:number) => console.log(`Start ${id}`)}
      id={1}
      title="Build a Todo App"
      description="Create a simple Todo application to practice Svelte concepts."
    />
    <TodoCard
    onStart={(id:number) => console.log(`Start ${id}`)}
      id={1}
      title="Deploy the App"
      description="Deploy the Todo app using Vercel or Netlify."
    />
  <TodoCard
  onStart={(id:number) => console.log(`Start ${id}`)}
      id={1}
    title="Set up Svelte"
    description="Use Vite to setup a new Svelte project."
  />
  </div>
</main>

<style>
</style>
