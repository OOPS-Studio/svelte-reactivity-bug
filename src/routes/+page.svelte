<script>
	import { browser } from '$app/environment';

	let text = "hello";

	if(browser){
                console.log("running");
		text = "goodbye";
	}
</script>

<div>{@html text}</div>