<script>
    let {name = "Web 1"} = $props()

</script>

<div>
    <img src="https://placehold.co/100" alt="placeholder">
        <aside>
            <h3>{name}</h3>
            <ul>
                <li>{Hobby 1}</li>
                <li>{Hobby 2}</li>
                <li>{Hobby 3}</li>
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

</style>