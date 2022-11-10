<script>
export default {
    name: 'SiteHeader'
}

</script>

<template>
    <header id="site_header">
        <div class="navbar d_flex">
            <img class="logo" width="80" src="../assets/img/dc-logo.png" alt="">
            <ul class="d_flex">
                <li><a href="">Characters</a></li>
                <li><a href="">Comics</a></li>
                <li><a href="">Movies</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">Games</a></li>
                <li><a href="">Collectibles</a></li>
                <li><a href="">Videos</a></li>
                <li><a href="">Fans</a></li>
                <li><a href="">News</a></li>
                <li><a href="">Shop</a></li>
            </ul>
        </div>
    </header>
</template>

<style>
.d_flex {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.navbar {
    background-color: white;
}

.navbar .logo {
    padding: 0.6rem 0;
}

.navbar ul {
    list-style: none;
}

.navbar li {
    padding: 1rem 1rem;
}

.navbar a {
    text-decoration: none;
    color: black;
    text-transform: uppercase;
    font-size: 0.8rem;
    font-weight: bold;
}

.navbar a:hover {
    color: blue;
    border-bottom: 4px solid blue;
}
</style>