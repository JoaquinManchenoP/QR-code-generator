<script>
	import LeftColMenu from '../components/LeftColumn/LeftColMenu.svelte';
	import CenterColumn from '../components/CenterColumn/CenterColumn.svelte';
	import RightColumn from '../components/RightColumn/RightColumn.svelte';
</script>

<div class="main__page flex h-screen bg-slate-100">
	<div class="col1 w-1/5 flex items-center justify-center ">
		<div class="left__column h-[700px] w-11/12 bg-white rounded-md">
			<LeftColMenu />
		</div>
	</div>
	<div class="col2 w-2/5 flex items-center justify-center">
		<div class="center__column h-[700px] w-11/12 bg-white rounded-md">
			<CenterColumn />
		</div>
	</div>
	<div class="col3 w-2/5 flex items-center justify-center">
		<div class="right__column h-[700px] w-11/12 bg-white rounded-md">
			<RightColumn />
		</div>
	</div>
</div>
