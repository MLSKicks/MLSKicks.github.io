<script>

</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap');
    :global(body) {
        font-family: "Oswald", sans-serif;
    }
    nav {
        display: flex;
        justify-content: right;
    }
    a {
        padding-left: 1%;
    }
</style>
<nav>
    <a href='/'>Home</a>
    <a href="/projects">Projects</a>
    <a href="/blog">Blog</a>
</nav>
<slot />
<footer>

</footer>