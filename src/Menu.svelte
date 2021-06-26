<script>
    import AudioPlayer, { stopAll } from "./AudioPlayer.svelte";
    let audioTracks = ["./audio/1.mp3", "./audio/2.mp3"];
</script>

<main>
    <button on:click={stopAll}> Stop all! </button>

    {#each audioTracks as src}
        <AudioPlayer {src} />
    {/each}
</main>

<style>
</style>
