<script setup>
</script>

<template>
    <section class="section" id="one">
        <div class="container">
            <h1>Colors</h1>
            <h3 class="box shaped border-gradient"><span class="text-gradient"><i class="bx bx-palette"></i></span></h3>
        </div>
        <article>
            <header>
                <h3>System</h3>
            </header>
            <div class="container centered">
                <div class="cube">
                    <div class="side primary top color-80"></div>
                    <div class="side primary left"></div>
                    <div class="side primary front color-60"></div>
                </div>
                <p class="text-primary capitalize">Primary</p>
                <div class="cube">
                    <div class="side success top color-80"></div>
                    <div class="side success left"></div>
                    <div class="side success front color-60"></div>
                </div>
                <p class="text-success capitalize">Success</p>
                <div class="cube">
                    <div class="side danger top color-80"></div>
                    <div class="side danger left"></div>
                    <div class="side danger front color-60"></div>
                </div>
                <p class="text-danger capitalize">Danger</p>
                <div class="cube">
                    <div class="side warn top color-80"></div>
                    <div class="side warn left"></div>
                    <div class="side warn front color-60"></div>
                </div>
                <p class="text-warn capitalize">Warn</p>
                <div class="cube">
                    <div class="side dark top color-80"></div>
                    <div class="side dark left"></div>
                    <div class="side dark front color-60"></div>
                </div>
                <p class="text-dark capitalize">Dark</p>
                <div class="cube">
                    <div class="side light top color-80"></div>
                    <div class="side light left"></div>
                    <div class="side light front color-60"></div>
                </div>
                <p class="text-light capitalize">Light</p>
            </div>
        </article>
        <article>
            <header>
                <h3>Tailwind Palette</h3>
            </header>
            <p>Tailwind's beautifully curated color palette has been included which includes 22 colors with 10 shades each, represented below. To reduce code footprint, this palette has only been included in the <code>:root</code> as pseudo-classes like <code>.slate-50, .cyan-500</code> and as background classes like <code>.bg-rose</code>.</p>
            <div class="grid-container col-6">
                <div class="card bg-slate text-sm capitalize">Slate</div>
                <div class="card bg-gray text-sm capitalize">Gray</div>
                <div class="card bg-zinc text-sm capitalize">Zinc</div>
                <div class="card bg-neutral text-sm capitalize">Neutral</div>
                <div class="card bg-stone text-sm capitalize">Stone</div>
                <div class="card bg-red text-sm capitalize">Red</div>
            </div>
            <div class="grid-container col-6">
                <div class="card bg-orange text-sm capitalize">Orange</div>
                <div class="card bg-amber text-sm capitalize">Amber</div>
                <div class="card bg-yellow text-sm capitalize">Yellow</div>
                <div class="card bg-lime text-sm capitalize">Lime</div>
                <div class="card bg-green text-sm capitalize">Green</div>
                <div class="card bg-emerald text-sm capitalize">Emerald</div>
            </div>
            <div class="grid-container col-6">
                <div class="card bg-teal text-sm capitalize">Teal</div>
                <div class="card bg-cyan text-sm capitalize">Cyan</div>
                <div class="card bg-sky text-sm capitalize">Sky</div>
                <div class="card bg-blue text-sm capitalize">Blue</div>
                <div class="card bg-indigo text-sm capitalize">Indigo</div>
                <div class="card bg-violet text-sm capitalize">Violet</div>
            </div>
            <div class="grid-container col-6">
                <div class="card bg-purple text-sm capitalize">Purple</div>
                <div class="card bg-fuchsia text-sm capitalize">Fuchsia</div>
                <div class="card bg-pink text-sm capitalize">Pink</div>
                <div class="card bg-rose text-sm capitalize">Rose</div>
                <div>&nbsp;</div>
                <div>&nbsp;</div>
            </div>
            <h4 class="hl">Opacity</h4>
            <p>A series of classes <code>.color-80, .color-60, .color-40, and .color-20</code> have been added to dynamically change the opacity of an element.</p>
            <div class="container">
                <div class="card bg-primary text-sm capitalize">Primary</div>
                <div class="card bg-primary color-80 text-sm capitalize">Primary 80</div>
                <div class="card bg-primary color-60 text-sm capitalize">Primary 60</div>
                <div class="card bg-primary color-40 text-sm capitalize">Primary 40</div>
                <div class="card bg-primary color-20 text-sm capitalize">Primary 20</div>
            </div>
        </article>
    </section>
</template>

<style scoped>

</style>
