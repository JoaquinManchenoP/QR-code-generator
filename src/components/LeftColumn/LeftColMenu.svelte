<script>
	import LeftColumnButton from '../CenterColumn/LeftColumnButton.svelte';
	import ColumnHeader from '../ColumnHeader.svelte';
</script>

<div class="left__col h-full w-full flex items-center justify-center">
	<div class="left__col__content h-[650px] w-4/6">
		<div class="title">
			<ColumnHeader headerText={'Destination'} />
		</div>
		<div class="buttons h-4/6 w-full grid grid-cols-2 gap-5">
			<div class="website">
				<LeftColumnButton iconName={'mdi:link-variant'} />
			</div>
			<div class="drive">
				<LeftColumnButton iconName={'tabler:brand-google-drive'} />
			</div>
			<div class="youtube">
				<LeftColumnButton iconName={'ant-design:youtube-outlined'} />
			</div>
			<div class="facebook">
				<LeftColumnButton iconName={'iconoir:facebook-squared'} />
			</div>
			<div class="col2">
				<LeftColumnButton iconName={'teenyicons:instagram-outline'} />
			</div>
			<div class="col3">
				<LeftColumnButton iconName={'ic:outline-email'} />
			</div>
			<div class="col1">
				<LeftColumnButton iconName={'material-symbols:contact-page-outline-sharp'} />
			</div>
		</div>
	</div>
</div>
