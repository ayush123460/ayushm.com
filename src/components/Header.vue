<template>
    <header>
        <div class="brand">
            <div class="logo">
                <img src="@/assets/logo.png" alt="Ayush M. Logo" width="60px" height="60px">
            </div>
            <div class="name">
                <span>Ayush</span>
                <span>Mukherjee.</span>
            </div>
        </div>
        <nav>
            <router-link class="active" to="#work">work</router-link>
            <router-link to="#about">about</router-link>
            <router-link to="#skills">skills</router-link>
            <router-link to="#contact">contact</router-link>
        </nav>
    </header>
</template>
