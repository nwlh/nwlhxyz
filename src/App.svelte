<script>
    let count = $state(0);

    function increment() {
        count += 100;
    }
</script>

<h1>nwlh.xyz</h1>

<button onclick={increment}>
    donated {count}
    {count === 1 ? "dollar" : "dollars"}
</button>

<style>
    h1 {
        color: goldenrod;
        font-family: "Comic Sans MS", cursive;
        font-size: 2em;
    }
</style>
