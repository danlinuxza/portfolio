<script>
    import { projects } from "$lib/data/projects";
</script>

<h1>Projects</h1>

{#each projects as project}
    <article>
        <h3>{project.title}</h3>
        <p>{project.description}</p>
        <a href={project.link} target="_blank">View Project</a>
    </article>
{/each}
