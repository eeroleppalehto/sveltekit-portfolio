<div class="topbar">
    <a href="/">portfolio</a>
    <nav>
        <a class="navigation-link" href="/">home</a>
        <a class="navigation-link" href="/about">about</a>
        <a class="navigation-link" href="/projects">projects</a>
        <a class="navigation-link" href="/contact">contact</a>
    </nav>
</div>

<style>
    .topbar {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-bottom: 4rem;
    }

    .topbar a {
        text-decoration: none;
        font-weight: bold;
        font-size: 1.5rem;
        text-decoration: none;
        color: #111111;
    }

    nav {
        display: flex;
        justify-content: space-between;
        gap: 3rem;
        margin-bottom: 1em;
    }

    .navigation-link {
        text-decoration: none;
        font-weight: bold;
        font-size: 1rem;
    }

    nav a:hover {
        color: #888888;
    }

    nav a:active {
        color: #888888;
    }

    

    @media screen and (max-width: 600px) {
        nav {
            display: hidden;
        }
    }
</style>