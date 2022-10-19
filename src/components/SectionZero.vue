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
                <p><span class="hl">Darksight</span> is a dark-themed, user interface composed of a series of re-usable,
                    responsive, material design components. <span class="hl">Darksight</span> was created in Vue, styled
                    with CSS, and lovingly crafted by Front-End Developer <a href="mailto:johndurtche@gmail.com"
                        target="_blank">John Durtche</a>
                    for use at <a href="https://www.entarisdnd.com">entarisdnd.com</a>. It serves as both a brand and style
                    guide for Entaris content, and a portfolio of work by its creator.</p>
            </div>
            <div class="grid-container col-4">
                <div class="grid-item box"><i class="bx bxl-vuejs"></i>VueJS</div>
                <div class="grid-item box"><i class="bx bxl-css3"></i>CSS3</div>
                <div class="grid-item box"><i class="bx bxl-sass"></i>SASS</div>
                <div class="grid-item box"><i class='bx bxs-cube' ></i>Boxicons</div>
            </div>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>How Is It Different?</h4>
            <p><span class="hl">Darksight</span> has been a passion project since it's conception in early 2022. It's
                creator describes it best:</p>
            <div class="box bg-primary-40">
                <span><i class="bx bxs-quote-alt-left bx-pull-left bx-lg"></i>A beautiful monstrosity and I love it. I
                    combined all the parts of various other existing frameworks to create Darksight. I spent months
                    pouring through the repositories and source code of front-end frameworks like Bootstrap, Vuetify,
                    Bulma, Tailwind, Core Elements, and Vuesax. These are arguably the best frameworks out there, yet
                    only one came close to exactly what I desired. I wanted something compact, powerful, and simple. I
                    knew I had to create what I wanted and Darksight is the child of that idea.</span>
                <cite class="text-sm capitalize">&mdash;John Durtche</cite>
            </div>
            <p></p>
            <p>These three principles of compact, powerful, and simple make <span class="text-primary">Darksight</span>
                unique.</p>
            <div class="grid-container col-3">
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Compact</h3>
                        <p class="align-left">You can use all of the framework by importing one cascading style sheet (CSS)
                        file&mdash;no JavaScript required. The annoying class name prefixes found in other frameworks
                        have been omitted (-vs-, -tw-, -v-, etc.), since they are understandable but unneccesary. A
                        limited color palette but with variations for both opacity and application of colors to text,
                        borders, backgrounds and more. Also, a minified version of the main stylesheet exists and future
                        versions will use SASS. The framework only exists as a dark theme&mdash;half the code required!
                    </p>
                    </div>
                </div>
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Powerful</h3>
                        <p class="align-left">Using the best of the latest HTML and CSS element tags, classes, pseudo-elements,
                        transitions, filters, and transforms, the framework has dozens of pre-built components that are
                        ready to include in your web projects and has many generic styles that can be applied to various
                        elements, giving you more flexibility in designing your own components.</p>
                    </div>
                </div>
                <div class="card grid-item">
                    <div class="card-content">
                        <h3 class="text-primary">Simple</h3>
                        <p class="align-left">Built from the ground with a minimalist, semantic-above-all-else approach to keep
                        the framework from devolving into a cluster of confusing class names and overriding, conflicting
                        styles like other frameworks, it contains class names that are divided into 7 major categories:
                        Colors, Typography, Elevation, Icons, Labels, Layout, and Components.</p>
                    </div>
                </div>
            </div>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>Show Me Around</h4>
            <p>Easily navigate each of <span class="hl">Darksight</span>'s eight <span
                    class="text-code">&lt;section&gt;</span>s using the <span class="text-code">.sidebar</span> on the
                left of your screen or the <span class="text-code">.topbar</span> at the top of your screen. Large headers and icons identify each section clearly.</p>
        </article>
        <article>
            <h4>&nbsp;</h4>
            <h4>Just Let Me Use Darksight Already!</h4>
            <p>Using the framework is now as easy as adding the following line of code into the top of your <span
                    class="text-code">&lt;head&gt;</span> element:</p>
            <div class="text-code code--box">
                &lt;<span class="text-danger">link rel</span>="<span class="text-success">stylesheet</span>" <span
                    class="text-danger">type</span>="<span class="text-success">text/css</span>" <span
                    class="text-danger">src</span>="<span class="text-success">darksight.css</span>" /&gt;
            </div>
        </article>
    </section>
</template>

<style scoped>
a,
a:link {
    text-decoration: none !important;
    border-bottom: 0 !important;
    margin: 0 0 !important;
    line-height: 1em !important;
}

.hero {
    background: linear-gradient(to top left, var(--slate-800) 0%, transparent 80%) !important;
}

.hero>h1 {
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    animation: moveInLeft 1.4s ease-out;
}

.hero>.label {
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    animation: moveInRight 1.4s ease-out;
}
</style>
