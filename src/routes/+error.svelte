<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Oops! {page.status}</h1>
	<p>{page.error?.message ?? "There was an issue processing your request."}</p>
	<a href="/">Return to the Semiotic homepage</a>
</main>
