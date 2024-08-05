<script>
    // export let image_src ="src";
    export let title;
    export let desc = "Card Description...";
    // export let btn_fc = () => {alert("Pressed!")};
    // export let btn_text = 'Click';
    export let link = 'link';
    export let tag = ['Javascript'];
</script>
<style>
    div {
        background-color: grey;
        align-items: right;
        justify-content: center;
        display: flex;
    }
</style>

<div>
    <!-- <slot name="image">
    <img src={image_src}>
    </slot> -->
    <slot name='title'>
        {#if title}
            <h4>{title}</h4>
        {:else}
            Placeholder Title
        {/if}
    </slot>
    <slot name="desc">
        {#if desc}
            {desc}
        {:else}
            Placeholder RTCSessionDescription
        {/if}
    </slot>
    <!-- <slot name="button">
        <button on:click={btn_fc}>{btn_text}</button>
    </slot> -->
    </div>

