<template>
    <header>
        <nav class="navbar navbar-expand-md navbar-color p-3 border-bottom  border-secondary">
        <div class="container-fluid">
            <router-link to="/" class="navbar-brand  brand-font fs-2 text-white">NinerUnite</router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav ms-auto gap-3">
                <li class="nav-item d-grid">
                    <router-link to="/signUp" class="btn nav-bar-btn-color">Sign Up</router-link>
                </li>
                <li class="nav-item d-grid">
                    <router-link to="/logIn" class="btn nav-bar-btn-color">Login</router-link>
                </li>
            </ul>
            </div>
        </div>
        </nav>
    </header>
</template>

<script>
export default {
    /* eslint-disable */
    name:'Header',
}
</script>

<style scoped>
.green {
    background-color: #005035;
}
.green_hover:hover {
    background-color: #026342;
}

.navbar-color {
    /* background-color:#ffffff; */
    background-color: #005035;
}

.nav-bar-btn-color {
    background-color: #A49665;
    color: white;
}

.hamburger-button {
    background-color: #A49665;
}

.nav-bar-btn-color:hover {
    background-color: #b9af88;
    color: white;
}

.nav-bar-btn-color:active {
    background-color: #b9af88;
    color: white;
}
</style>
