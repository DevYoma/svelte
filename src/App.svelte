
<script>

	import FeedbackList from './components/FeedbackList.svelte'

	let feedback = [
		{
			id:1,
			rating: 10,
			text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores impedit unde, provident voluptates illo odit.'
		},
		{
			id:2,
			rating: 9,
			text: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magni quidem labore voluptatum necessitatibus doloribus enim.'
		},
		{
			id: 3,
			rating: 8,
			text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos quae ducimus velit cupiditate magnam! Fugit.'
		}
	]
</script>

<main class="container">
	<FeedbackList feedback={feedback}/>
</main>

<style>
	
</style>