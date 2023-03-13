<template>
    <header>
        <nuxt-link to="/">
            <h1 >Victoria Loibl</h1>
            <!-- <img class="profile-picture" src="../assets/profile.JPG" alt=""> -->

        </nuxt-link>

        <nav>
        <nuxt-link to="/" class="nav-child">Home</nuxt-link>
        <nuxt-link to="/about" class="nav-child">About</nuxt-link>
        </nav>
    </header>
</template>

<style>

* {
    margin: 0;
    padding: 0;
    color: white;

}

header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    width: 100%;
    height: 200px;
    background-color: #40826D;
    padding-top: 50px;
    padding-left: 50px;

}

.title {
    font-size: 48px;
    justify-self: flex-start;
}

nav {
    width: 20%;
    display: flex;
    justify-content: space-evenly;
    font-size: large;
    align-items: baseline;

}

.profile-picture {
    height: 400px;
    object-fit: contain;
    border-radius: 50px;
}

.nav-child {
    padding: 20px;
    border-radius: 15px;
    background-color: #40826D;
}

.nav-child:hover {
    background-color: #66ccac;
}

.nav-child:checked {
    background-color: antiquewhite;
}

</style>