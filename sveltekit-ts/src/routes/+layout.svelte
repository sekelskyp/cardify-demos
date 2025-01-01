<script>
    let { children } = $props();
</script>

<header>
    <nav>
        <a href="/card">Card</a>
        <a href="/features">Features</a>
        <a href="/pricing">Pricing</a>
        <a href="/cart">Cart</a>
        <a href="/login">Login</a>
        <a href="/register">Register</a>
    </nav>
</header>

{@render children()}

<footer>
    <nav>
        <a href="/card">Card</a>
        <a href="/features">Features</a>
        <a href="/pricing">Pricing</a>
    </nav>
</footer>
