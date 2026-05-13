<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<img src="https://play-lh.googleusercontent.com/1-hPxafOxdYpYZEOKzNIkSP43HXCNftVJVttoo4ucl7rsMASXW3Xr6GlXURCubE1tA=w3840-h2160-rw" width="400px" alt="google">
<div id="google">
<textarea>Please google {html}</textarea>
<button class="btn">Google</button>
</div>
<footer>This is the footer</footer>

<script>
    let html='Google';
</script>

<style>
    textarea{
        color: blueviolet;
        background-color: goldenrod;
        width: 500px;
        padding: 10px;
    }

    .btn{
        width: 200px;
        height: 35px;
        background-color: cornflowerblue;
    }
    #google{
        background-color: aqua;
    }
    footer{
        position: inherit;
        margin-top: 200px;
    }
</style>