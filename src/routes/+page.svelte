<script>
	import LeftColMenu from '../components/LeftColumn/LeftColMenu.svelte';
	import CenterColumn from '../components/CenterColumn/CenterColumn.svelte';
	import RightColumn from '../components/RightColumn/RightColumn.svelte';
</script>

<div class="main__page flex bg-green-400 h-screen">
	<div class="col1 w-1/3 bg-orange-300 flex items-center justify-center ">
		<div class="left__column h-[700px] w-11/12 bg-red-600 rounded-md">
			<LeftColMenu />
		</div>
	</div>
	<div class="col2 w-1/3 bg-purple-400 flex items-center justify-center">
		<div class="center__column h-[700px] w-11/12 bg-red-600 rounded-md">
			<CenterColumn />
		</div>
	</div>
	<div class="col3 w-1/3 flex items-center justify-center">
		<div class="right__column h-[700px] w-11/12 bg-red-600 rounded-md">
			<RightColumn />
		</div>
	</div>
</div>
