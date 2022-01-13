<script>
    import FeedbackItem from './FeedbackItem.svelte'
    export let feedback = []
    // console.log(feedback)
</script>

<main>
    {#each feedback as fb (fb.id)}
        <!-- <h3>{fb.rating}</h3> -->
        <FeedbackItem {fb}/>
    {/each}
</main>