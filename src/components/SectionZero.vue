<script setup>

</script>

<template>
    <section class="hero">
        <h1 class="hl capitalize">DARKSIGHT</h1>
        <p class="label">A Front-End Framework By John Durtche</p>
    </section>
    <section class="section" id="zero">
        <div class="container">
            <h1>Darksight</h1>
            <h3 class="box shaped"><i class="bx bxs-low-vision"></i></h3>
        </div>
        <article>
            <header>
                <h3>What is Darksight?</h3>
            </header>
            <div class="container">
                <p>
                    <span class="hl">Darksight</span> is a dark-themed, user interface composed of a series of re-usable,
                    responsive, material design components. <span class="hl">Darksight</span> was created in Vue, styled
                    with SASS and CSS, and lovingly crafted by Front-End Developer <a href="mailto:johndurtche@gmail.com"
                                                                             target="_blank">John Durtche</a>
                    for use at <a href="https://www.entarisdnd.com">entarisdnd.com</a>. It serves as both a brand and style
                    guide for Entaris content, and a portfolio of work by its creator.
                </p>
            </div>
            <div class="grid-container col-4">
                <div class="grid-item box"><i class="bx bxl-vuejs"></i>VueJS</div>
                <div class="grid-item box"><i class="bx bxl-css3"></i>CSS3</div>
                <div class="grid-item box"><i class="bx bxl-sass"></i>SASS</div>
                <div class="grid-item box"><i class='bx bxs-cube'></i>Boxicons</div>
            </div>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>How Is It Different?</h4>
            <p>
                <span class="hl">Darksight</span> has been a passion project since it's conception in early 2022. It's
                creator describes it best:
            </p>
            <div class="box bg-primary-40">
                <span>
                    <i class="bx bxs-quote-alt-left bx-pull-left bx-lg"></i>A beautiful monstrosity and I love it. I
                    combined all the parts of various other existing frameworks to create Darksight. I spent months
                    pouring through the repositories and source code of front-end frameworks like Bootstrap, Vuetify,
                    Bulma, Tailwind, Core Elements, and Vuesax. These are arguably the best frameworks out there, yet
                    only one came close to exactly what I desired. I wanted something compact, powerful, and simple. I
                    knew I had to create what I wanted and Darksight is the child of that idea.
                </span>
                <cite class="text-sm capitalize">&mdash;John Durtche</cite>
            </div>
            <p></p>
            <p>
                These three principles of compact, powerful, and simple make <span class="text-primary">Darksight</span>
                unique.
            </p>
            <div class="grid-container col-3">
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Compact</h3>
                            <ul class="bx-ul align-left">
                                <li><i class="bx bx-right-arrow bx-xs text-primary"></i>
                                    One cascading style sheet (CSS) file&mdash;no JavaScript required.
                                </li>
                                <li><i class="bx bx-right-arrow bx-xs text-primary"></i>
                                    No annoying class name prefixes found in other frameworks (-vs-, -tw-, -v-, etc.)&mdash;these are understandable but unneccesary.
                                </li>
                                <li><i class="bx bx-right-arrow bx-xs text-primary"></i>
                                    Tailwind color palette with variations for both opacity and application of colors to text,
                                    borders, backgrounds and more.
                                </li>
                                <li><i class="bx bx-right-arrow bx-xs text-primary"></i>
                                    Developed with Vite and SASS for cleaner CSS compilation.
                                </li>
                                <li><i class="bx bx-right-arrow bx-xs text-primary"></i>
                                    Dark theme only&mdash;half the code required!
                                </li>
                            </ul>
                    </div>
                </div>
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Powerful</h3>
                        <ul class="bx-ul align-left">
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Latest HTML5 and CSS3 element tags, classes, pseudo-elements, transitions, filters, transforms, and animations!
                            </li>
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Dozens of pre-built, ready-to-use components!
                            </li>
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Generic styles that can be applied to various elements&mdash;more flexibility in designing your own custom components.
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Simple</h3>
                        <ul class="bx-ul align-left">
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Hand-crafted with minimalist, semantic-above-all-else approach.
                            </li>
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Organized and easily identifiable class names and styles.
                            </li>
                            <li>
                                <i class="bx bx-right-arrow bx-xs text-primary"></i>
                                Index provided with clear code divisions based on the developmental SASS files:
                                    <ul class="bx-ul sub-list text-sm">
                                        <li>Variables, Mixins, Layout, Colors, Typography, Icons, Navigation, Elevation, Buttons, Tabs-Accordion, Alerts, Avatars, Chips, Tooltips, Forms, Cards, Modals, Materials, Breakpoints, and Animations.</li>
                                    </ul>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>Show Me Around</h4>
            <p>
                Easily navigate each of <span class="hl">Darksight</span>'s eight <span class="text-code">&lt;section&gt;</span>s using the <span class="text-code">.sidebar</span> on the
                left of your screen or the <span class="text-code">.topbar</span> at the top of your screen. Large headers and icons identify each section clearly.
            </p>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>Just Let Me Use Darksight Already!</h4>
            <p>
                Using the framework is now as easy as adding the following line of code into the top of your <span class="text-code">&lt;head&gt;</span> element:
            </p>
            <div class="text-code code--box">
                &lt;<span class="text-danger">link rel</span>="<span class="text-success">stylesheet</span>" <span class="text-danger">type</span>="<span class="text-success">text/css</span>" <span class="text-danger">src</span>="<span class="text-success">darksight.css</span>" /&gt;
            </div>
        </article>
    </section>
</template>

<style scoped>
    .hero {
        background: linear-gradient(to top left, var(--slate-800) 0%, transparent 80%) !important;
    }

        .hero > h1 {
            -moz-backface-visibility: hidden;
            backface-visibility: hidden;
            animation: moveInLeft 1.4s ease-out;
        }

        .hero > .label {
            -moz-backface-visibility: hidden;
            backface-visibility: hidden;
            animation: moveInRight 1.4s ease-out;
        }
    .sub-list {
        margin: 0 1em;
    }
</style>
