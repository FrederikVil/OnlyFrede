<div style="display: flex; justify-content: center;">
    <video src="./frede.mp4" autoplay controls loop/>
</div>
<script>
	import { onMount } from "svelte";

    onMount(() => {
        document.getElementsByTagName('video')[0].play()
    })
</script>dfdff