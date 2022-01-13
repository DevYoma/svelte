<script>
    import Card from './Card.svelte'
    export let fb
    console.log(fb)
</script>

<!-- <main>
    <h1>FeedbackItem component</h1>
</main> -->

<Card>
    <div class="num__display">
        {fb.rating}
    </div>
    <div class="close">X</div>
    <div class="text__display">
        {fb.text}
    </div>
</Card>

<style>
    .num__display{
        position: absolute;
        top: -10px;
        left: -10px;
        width: 50px;
        height: 50px;
        background: #ff6a95;
        color: #fff;
        border: 1px solid #eee;
        border-radius: 50%;
        padding: 10px;
        text-align: center;
        font-size: 10px;
    }

    .close{
        position: absolute;
        top: 10px;
        right: 20px;
        cursor: pointer;
    }
</style>