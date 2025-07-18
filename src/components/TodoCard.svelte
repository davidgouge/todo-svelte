<script lang="ts">
    let {title, description, id, onStart} = $props(); 
</script>

<div class="card todo-card">
    <div class="card-header">{title}</div>
    <div class="card-body">{description}</div>
    <div class="card-footer">
        <a href="#" onclick={onStart(id)} class="card-link">Start</a>
    </div>
</div>

<style>
    .todo-card {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        
        margin: 1rem;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        border-radius: 8px;
        background: #fff;
        transition: box-shadow 0.2s;
    }
    .todo-card:hover {
        box-shadow: 0 4px 16px rgba(0,0,0,0.15);
    }
</style>