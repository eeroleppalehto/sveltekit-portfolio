<script>
    import Project from './Project.svelte'
    import mock from '$lib/assets/mock.jpg';
</script>

<div class="name-container">
    <div>
        <h1 class="name">Eero Leppälehto</h1>
    </div>
    <p class="description">A fullstack developer with experience in plaa plaa</p>
</div>
<div class="projects">
    <Project 
        image={mock} 
        header={"01 / Jahtirekisteri".toUpperCase()} 
        description="A fullstack web application for managing hunting events and game harvests" 
        technologies="TypeScript" 
    />
    <Project 
        image={mock} 
        header={"02 / Jahtirekisteri".toUpperCase()} 
        description="A fullstack web application for managing hunting events and game harvests" 
        technologies="TypeScript" 
    />
    <Project 
        image={mock} 
        header={"03 / Jahtirekisteri".toUpperCase()} 
        description="A fullstack web application for managing hunting events and game harvests" 
        technologies="TypeScript" 
    />
    <!-- NEEDS MORE WHITESPACE -->
</div>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    .name-container {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: flex-end;
        margin-bottom: 8rem;
    }

    .name {
        font-size: 3.5rem;
        max-width: 20rem;
        font-weight: 00;
        flex: 1;
    }

    .description {
        max-width: 25rem;
        line-height: 1.8;
        flex: 2;
    }
</style>