<script setup>
function sidebar() {
    document.getElementById("sidebar").classList.toggle("hide");
}
</script>

<template>
    <header class="topbar is-sticky glass">
        <div class="tb-left">
            <button class="is-hamburg" @click="sidebar()">
                <i class="bx bx-menu"></i>
            </button>
            <h4 class="text-primary capitalize">DARKSIGHT</h4>
        </div>
        <div class="tb-mid">
            <div class="tb-container">
                <a class="tb tile ripple" onclick="window.location.href='#zero';window.scrollBy(0,-88);"><i class="bx bxs-low-vision"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#one';window.scrollBy(0,-88);"><i class="bx bx-palette"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#two';window.scrollBy(0,-88);"><i class="bx bx-text"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#three';window.scrollBy(0,-88);"><i class="bx bx-layer"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#four';window.scrollBy(0,-88);"><i class="bx bxs-cube"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#five';window.scrollBy(0,-88);"><i class="bx bx-label"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#six';window.scrollBy(0,-88);"><i class="bx bx-grid"></i></a>
                <a class="tb tile ripple" onclick="window.location.href='#seven';window.scrollBy(0,-88);"><i class="bx bxs-component"></i></a>
            </div>
        </div>
        <div class="tb-right">
            <button class="btn--primary ripple" onclick="window.open('https://www.github.com/thejohnnathan/darksight_v_1_1_x')">
                <i class="bx bxl-github bx-burst"></i>
                Visit Our Github
            </button>
        </div>
    </header>
</template>

<style scoped>
.tb-left>h4>a {
    border: none !important;
}

.is-hamburg:hover {
    box-shadow: none !important;
}
</style>