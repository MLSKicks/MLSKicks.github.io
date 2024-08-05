<script>
    import Card from "$lib/components/Card.svelte";
</script>
<style>
    ul {
        column-count: 2;
    }
</style>
<h1>Projects</h1>
<h2>Software Engineering</h2>
<Card title="Point of Sale Application">
    <svelte:fragment slot="desc">
        <p>React Native Application</p>
        <p>Point of Sale App based around Hospitality.</p>
    </svelte:fragment>
</Card>
<Card title="Bartender Application">
    <svelte:fragment slot="desc">
        <p>React Native Application</p>
        <p>Bartender App</p>
    </svelte:fragment>
</Card>
<Card title="Robot Search Algorithm">
    <svelte:fragment slot="desc">
        <p>Algorithm</p>
        <p>Robotic Path Planning</p>
    </svelte:fragment>
</Card>
<Card title="">
    <svelte:fragment slot="desc">
    </svelte:fragment>
</Card>
