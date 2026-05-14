<script>
    let {name = "Web 1", image="https://placehold.co/100", hobby="Guitar"} = $props()

</script>

<div>
    <img src="{image}" alt="placeholder">
        <aside>
            <h3>{name}</h3>
            <ul>
                <li>{hobby}</li>
                <li></li>
                <li></li>
            </ul>
        </aside>
</div>



<style>
div{
    color:palevioletred;
    background-color: blueviolet;
    display: flex;
    padding: 1em;
    margin-bottom: 1em;
    border:1em solid salmon;
    gap:1em;
    max-width: 400px;
}

img{
    width:300px;
}
</style>