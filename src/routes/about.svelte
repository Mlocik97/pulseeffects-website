<script>
	import { name } from "../../static/manifest.json";
	import * as data from "../data/data.json";
</script>

<svelte:head>
	<title>{name}</title>
</svelte:head>

<div>{data}</div>
