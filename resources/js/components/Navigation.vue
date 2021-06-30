<template>
    <nav>
        <a href="/">Accueil</a>
        <a href="portfolio">Portfolio</a>
        <a href="contact">Me contacter</a>
    </nav>
</template>

<script>
export default {

}
</script>

<style>
nav{
    display: flex;
    justify-content: space-between;
    position: sticky;
    padding-right: 45px;
    padding-left: 45px;
}
a{
    text-decoration: none;
    color: #ff4b37;
    padding-top: 20px;
    font-weight: 80;
    font-size: 25px;
    font-family: Raleway;
    letter-spacing: 0.6rem;
}
</style>