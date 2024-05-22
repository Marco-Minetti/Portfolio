<script>
    import Header from './Header.svelte';
    import './style.css';
    import fondo from '$lib/img/sfondo.jpg';
</script>
<body>    

    <Header />

    <main>
        <div class="super_container">
            <slot />
        </div>
    </main>

    <footer>
        <p>
            Sito creato da <a href="https://github.com/Marco-Minetti/">Marco Minetti</a>
        </p>
    </footer>

</body>

<style>

    footer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 12px;
        font-size: 10px;
    }

    .super_container {
        width: 60%;
        justify-content: center;
        margin: 0 auto;
        background-color: rgb(213, 255, 243);
        padding: 10px 0px 50px 50px;
        border-radius: 100px;
    }


</style>