<template>
    <header>
        <nav>
            <ul>
                <li><nuxt-link to="/">Main</nuxt-link></li>
                <li><nuxt-link to="/home">Home</nuxt-link></li>
                <li><nuxt-link to="/about">About</nuxt-link></li>
            </ul>
        </nav>
    </header>
</template>
<script>
export default {
    name: 'Header',
};
</script>
<style scoped>
nav ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    padding: 10px;
    background-color: #f8f8f8;
}
nav ul li {
    margin: 0 10px;
}
</style>