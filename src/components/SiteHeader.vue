<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
            linkNavbar: [
                {
                    name: 'Characters',
                    href: '#'
                },
                {
                    name: 'Comics',
                    href: '#'
                },
                {
                    name: 'Movies',
                    href: '#'
                },
                {
                    name: 'TV',
                    href: '#'
                },
                {
                    name: 'Games',
                    href: '#'
                },
                {
                    name: 'Collectibles',
                    href: '#'
                },
                {
                    name: 'Videos',
                    href: '#'
                },
                {
                    name: 'Fans',
                    href: '#'
                },
                {
                    name: 'News',
                    href: '#'
                },
                {
                    name: 'Shop',
                    href: '#'
                },
            ]
        }
    },
}

</script>

<template>
    <header id="site_header">
        <div class="navbar d_flex">
            <img class="logo" width="80" src="../assets/img/dc-logo.png" alt="">
            <ul class="d_flex">
                <li v-for="link in linkNavbar"><a href="{{ link.href }}">{{ link.name }}</a></li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

/* header {

    ul {
        list-style: none;
        display: flex;
    }
} */

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