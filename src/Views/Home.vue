<template>
    <section>
        <div>
            <span class="hello-span">Hello!</span>
            <h1>I'm <span class="name">Jimmy Giraldo</span></h1>
            <span class="profession-span">Software Developer</span>
            <div class="buttons-container">
                <button class="primary">
                    Contact
                </button>
                
                <button class="secondary">
                    My Projects
                </button>
            </div>
        </div>

        <div>
            My image
        </div>
    </section>
</template>

<style>
    .hello-span {
        color: var(--color-primary);
        letter-spacing: 0.15rem;
    }

    .name{
        color: var(--color-primary);
    }

    .profession-span{
        font-size: 1.5rem;
    }

    h1{
        font-size: 2.5rem;
        margin: 0;
        font-weight: 1000;
    }

    .buttons-container{
        display: flex;
        gap: 1rem;
        margin-top: 1rem;
    }

    section {
        display: flex;
        justify-content: space-between;
        gap: 2rem;
        padding: 2rem;
        align-items: center;
        justify-self: center;
    }
</style>
