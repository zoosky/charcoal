<template>
    <ch-navbar class="is-fixed-top is-dark">
        <router-link
            class="navbar-item"
            slot="navbar-brand"
            to="/"
        >
            <span class="icon">
                <i class="fa fa-home"></i>
            </span>
        </router-link>
        <router-link
            class="navbar-item"
            slot="navbar-end"
            to="/about"
        >
            <span class="icon">
                <i class="fa fa-user"></i>
            </span>
            About
        </router-link>
    </ch-navbar>
</template>

<script>

import ChNavbar from '../ch-components/components/Navbar.vue'

export default {
    components: {
        ChNavbar
    }
}

</script>

<style lang="scss"></style>