<script setup>

</script>

<template>
    <aside class="navbar" id="sidebar">
        <nav>
            <menu>
                <li class="box ripple" onclick="window.location.href='#zero';window.scrollBy(0,-88);">
                    <span><i class="bx bxs-low-vision"></i></span>
                    <span>Darksight</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#one';window.scrollBy(0,-88);">
                    <span><i class="bx bx-palette"></i></span>
                    <span>Colors</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#two';window.scrollBy(0,-88);">
                    <span><i class="bx bx-text"></i></span>
                    <span>Typography</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#three';window.scrollBy(0,-88);">
                    <span><i class="bx bx-layer"></i></span>
                    <span>Elevation</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#four';window.scrollBy(0,-88);">
                    <span><i class="bx bxs-cube"></i></span>
                    <span>Icons</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#five';window.scrollBy(0,-88);">
                    <span><i class="bx bx-label"></i></span>
                    <span>Labels</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#six';window.scrollBy(0,-88);">
                    <span><i class="bx bx-grid"></i></span>
                    <span>Layout</span>
                </li>
                <li class="box ripple" onclick="window.location.href='#seven';window.scrollBy(0,-88);">
                    <span><i class="bx bxs-component"></i></span>
                    <span>Components</span>
                </li>
            </menu>
        </nav>
    </aside>
</template>

<style>
.hideSidebar {
    width: 0;
    display: none;
}

menu {
    padding-top: 0.5em;
}

menu>nav>.box {
    justify-content: space-between !important;
    border: 0px solid transparent !important;
}

menu>li>span>i {
    font-size: 1.25em !important;
    max-width: 1em !important;
    margin: 0 0.25em 0 -0.5em !important;
}

nav>menu>li>span:first-child {
    font-size: 1.5em !important;
    margin-right: 0;
    padding: 0.85em;
    line-height: 1em;
}

menu>li>span:last-child {
    font-size: 1.5em !important;
    padding: 0;
    width: 100%;
}
@media (max-width: 1440px) {
    .navbar, nav > menu {
        width: 4.5em !important;
    }
    #sidebar {
        max-width: 4.5em !important;
    }
    menu>li {
        max-width: 6em !important;
        width: 6em !important
    }
    menu>li:hover {
        padding-left: 0.5em !important;
    }
    menu>li>span {
        padding: 0em 1em !important;
    }
}
</style>
