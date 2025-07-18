<script lang="ts">
  import "bootstrap/dist/css/bootstrap.css";
  import TodoCard from "./components/TodoCard.svelte";
</script>

<main>
  <div class="todo-cards-container">
    <TodoCard
      onStart={(id) => console.log(`Start ${id}`)}
      title="Learn Svelte"
      description="Understand the basics of Svelte and its reactivity model."
    />
    <TodoCard
      title="Build a Todo App"
      description="Create a simple Todo application to practice Svelte concepts."
    />
    <TodoCard
      title="Deploy the App"
      description="Deploy the Todo app using Vercel or Netlify."
    />
  <TodoCard
    title="Set up Svelte"
    description="Use Vite to setup a new Svelte project."
  />
  </div>
</main>

<style>
</style>
