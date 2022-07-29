<script>
    let number1 = 0
    let number2 = 0
</script>

<input bind:value={number1} type="number" />
<input bind:value={number2} type="number" />

<p>{number1} + {number2} = {number1 + number2} ✨</p>

<style>
    p {
        color: green;
    }
</style>