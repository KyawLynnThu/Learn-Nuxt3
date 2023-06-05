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

        <h2>About</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aut ut, cum similique, officia expedita provident dicta, suscipit necessitatibus deserunt dolorum nostrum? Totam, deserunt recusandae a nihil debitis maiores voluptatum reiciendis!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolores quia sequi repellat odit sunt obcaecati earum laboriosam accusamus dolor suscipit atque rerum voluptatum, alias quod autem ullam ipsum temporibus!</p>
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