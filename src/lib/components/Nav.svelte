<script>
  import { resolve } from '$app/paths';
</script>

<nav>
  <a href="{resolve('/')}" >Home</a>
  <a href="{resolve('/about')}" >About</a>
  <a href="{resolve('/projects')}" >Projects</a>
  <a href="{resolve('/contact')}" >Contact</a>
</nav>

<style>
  nav {
    display: flex;
    gap: 1.5rem;
    padding: 1rem;
    border-bottom: 1px solid #ddd;
  }

  a {
    text-decoration: none;
    font-weight: 600;
  }
</style>
