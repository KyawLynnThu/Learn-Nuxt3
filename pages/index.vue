<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Nuxt3</NuxtLink>
                <ul>
                    <li>
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/products">Products</NuxtLink>
                    </li>
                </ul>
            </nav>
        </header>

        <h2>Home</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum nulla nisi illum natus nemo qui reprehenderit odit repellendus dolore at veritatis perspiciatis vitae nobis voluptatem quisquam, ab sunt repudiandae nihil!</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto autem tempora id, obcaecati voluptates cum fuga impedit ipsum cupiditate. Dolor laborum officiis numquam eveniet animi optio quia omnis, quaerat repellat.</p>
    </div>
</template>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
p {
    margin: 20px 0;
}
</style>