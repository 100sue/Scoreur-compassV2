<template>
    <aside>
        <div class="logo">
            <img src="../assets/compass.png" alt="logo du site">
        </div>
        <div class="menu-toggle-wrap">
            
        </div>
    </aside>

</template>

<script>
</script>

<style>

</style>

<style lang="scss" >
aside {
    display: flex;
    flex-direction: column;
    width: calc(2rem + 32px);
    min-height: 100vh;
    overflow: hidden;
    padding: 1rem;

    background-color: var(--dark);
    color: var(--light);

    transition: 0.2s ease-out;

    .logo {
        margin-bottom: 1rem;
        img {
            width: 2rem;
        }
    }

    @media (max-width: 768px) {
        position: fixed;
        z-index: 99;
    }
}
</style>
