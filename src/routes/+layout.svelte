<header>
    <a href="/">
        <div class="logo container">
            <img src="/logo.svg" alt="Logo" class="logo" />
            <h1>Science Informatique</h1>
        </div>
    </a>
</header>
<slot />

<style>
    header {
        border-bottom: 1px solid rgba(16, 24, 40, 0.05);
    }
    .logo {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 9px;
        padding: 10px 0px;
    }
    a {
        text-decoration: none;
        color: black;
    }
    @media (max-width: 400px) {
        .logo > h1 {
            font-size: 1.46rem;
        }
    }
</style>
