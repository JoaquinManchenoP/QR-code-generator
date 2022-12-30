<script>
	import LeftColumnButton from '../CenterColumn/LeftColumnButton.svelte';
</script>

<div class="left__col h-full w-full flex items-center justify-center">
	<div class="left__col__content h-[650px] w-4/6 bg-green-400">
		<div class="buttons">
			<div class="website__button">
				<LeftColumnButton iconName={'mdi:link-variant'} />
			</div>
			<div class="google__doc__button">
				<LeftColumnButton iconName={'mdi:google-drive'} />
			</div>
		</div>
	</div>
</div>
