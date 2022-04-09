<script>
    export let type;
</script>

<button class={type}><slot/></button>

<style>
    button {
        background-color: transparent;
        border: none;
        background-image: none;
        color: white;
        padding: 0;
        text-align: left;
    }

    button:hover {
        text-decoration: underline;
    }
</style>