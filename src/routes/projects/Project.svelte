<script lang="ts">
    import TopRight from 'virtual:icons/teenyicons/top-right-outline';
    export let image: string;
    export let header: string;
    export let description: string;
    export let technologies: string;
</script>

<div class="project-card">
    <div class="project-card-textarea" >
        <h2 class="project-header">{header}</h2>
        <p class="project-description">{description}</p>
        <p class="project-technologies">{technologies}</p>
        <a href="/projects/jahtirekisteri" class="project-link">Read more</a>
        <TopRight />
    </div>
    <img loading="lazy" src={image} alt="mock" class="project-card-image" />
</div>
<hr>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    .project-card {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        gap: 2.2rem;
        margin: 6rem 0;
    }

    .project-card-textarea {
        display: flex;
        flex: 1;
        flex-direction: column;
        justify-content: space-between;
        gap: 1rem;
    }

    .project-header {
        font-size: 1.4rem;
        font-weight: 600;
    }

    .project-description {
        font-size: 1.2rem;
        font-weight: 400;
    }

    .project-technologies {
        color: #666;
        font-size: 1.2rem;
        font-weight: 400;
    }

    .project-link {
        color: #000;
        font-size: 1.2rem;
        font-weight: 400;
        text-decoration: underline;
    }

    .project-card-image {
        display: flex;
        flex: 1;
        max-width: 50%;
        height: auto;
    }

    @media screen and (max-width: 600px) {
        .project-card {
            flex-direction: column-reverse;
            align-items: center;
            margin: 6rem 1.5rem;
        }

        .project-card-image {
            max-width: 100%;
        }
    }
</style>