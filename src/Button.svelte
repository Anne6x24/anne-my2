<script>
    export let type;
</script>

<a href="/" class={type}><slot/></a>

<style>
    a {
        background-color: transparent;
        border: none;
        background-image: none;
        color: white;
        padding: 0;
        text-align: left;
    }

    a:hover {
        text-decoration: underline;
    }
</style>