<script setup>
    import Modal from './Modal.vue';

    function showModal() {
        document.getElementById("dialog").classList.toggle("hide");
    }
</script>

<template>
    <section class="section" id="seven">
        <div class="container">
            <h1>Components</h1>
            <h3 class="box shaped"><i class="bx bxs-component"></i></h3>
        </div>
        <article class="centered">
            <h4 class="capitalized text-primary hl">Buttons</h4>
            <div class="container">
                <div class="flex-item">
                    <h5 class="box">Button Size</h5>
                    <div>
                        <button class="sm btn--primary" title="">
                            <i class="bx bx-check"></i>
                            Small
                        </button>
                        <button class="sm outlined" title="">
                            <i class="bx bx-check"></i>
                            Small
                        </button>
                        <button class="sm pill" title="">Small</button>
                        <button class="sm is-icon" title="">
                            <i class="bx bx-cog"></i>
                        </button>
                        <br />
                        <button class="btn--primary" title="">
                            <i class="bx bx-check"></i>
                            Medium
                        </button>
                        <button class="outlined" title="">
                            <i class="bx bx-check"></i>
                            Medium
                        </button>
                        <button class="pill" title="">
                            Medium
                        </button>
                        <button class="is-icon" title="">
                            <i class="bx bx-cog"></i>
                        </button>
                        <br />
                        <button class="lg btn--primary" title="">
                            <i class="bx bx-check"></i>
                            Large
                        </button>
                        <button class="lg outlined" title="">
                            <i class="bx bx-check"></i>
                            Large
                        </button>
                        <button class="lg pill" title="">
                            Large
                        </button>
                        <button class="lg is-icon" title="">
                            <i class="bx bx-cog"></i>
                        </button>
                    </div>
                </div>
                <div class="flex-item">
                    <h5 class="box">Button Label Style</h5>
                    <div>
                        <div class="text-light text-sm">Clipped</div>
                        <br />
                        <button class="btn--primary clipped" title="">Button</button>
                    </div>
                    <div>
                        <div class="text-light text-sm">Text Only</div>
                        <br />
                        <button class="btn--primary" title="">Button</button>
                    </div>
                    <div>
                        <div class="text-light text-sm">Outlined</div>
                        <br />
                        <button class="btn--primary outlined" title="">Button</button>
                    </div>
                    <div>
                        <div class="text-light text-sm">Centered - Left Icon</div>
                        <br />
                        <button class="btn--primary" title="">
                            <i class="bx bx-check"></i>
                            Button
                        </button>
                    </div>
                    <div>
                        <div class="text-light text-sm">Centered - Right Icon</div>
                        <br />
                        <button class="btn--primary" title="">
                            Button
                            <i class="bx bx-check dbl"></i>
                        </button>
                    </div>
                    <div>
                        <div class="text-light text-sm">Double Icon - Dropdowns and modals</div>
                        <br />
                        <button class="btn--primary" title="">
                            <i class="bx bx-check"></i>
                            Button
                            <i class="bx bx-x dbl"></i>
                        </button>
                    </div>
                </div>
            </div>
        </article>
        <article class="centered">
            <div class="container">
                <h5 class="box">Base Guidelines</h5>
                <div>
                    <div class="text-light text-sm">With Ripple</div>
                    <br />
                    <button class="btn--primary ripple" title="">Button</button>
                </div>
                <div>
                    <div class="text-light text-sm">Normal</div>
                    <br />
                    <button class="btn--primary" title="">Button</button>
                </div>
                <div>
                    <div class="text-light text-sm">Hover</div>
                    <br />
                    <button class="btn--primary hover" title="">
                        Button
                    </button>
                </div>
                <div>
                    <div class="text-light text-sm">Active</div>
                    <br />
                    <button class="btn--primary active" title="">
                        Button
                    </button>
                </div>
                <div>
                    <div class="text-light text-sm">Focused</div>
                    <br />
                    <button class="btn--primary focused" title="">
                        Button
                    </button>
                </div>
                <div>
                    <div class="text-light text-sm">Disabled</div>
                    <br />
                    <button class="btn--primary disabled" disabled title="">
                        Button
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4 class="capitalized text-primary hl">Accordion</h4>
            <div class="container box">
                <details class="accordion">
                    <summary>First Accordion Header</summary>
                    <p class="content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                        ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit
                        in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                        cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                    </p>
                </details>
                <details class="accordion">
                    <summary>Second Accordion Header</summary>
                    <p class="content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                        ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit
                        in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                        cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                    </p>
                </details>
                <details class="accordion">
                    <summary>Third Accordion Header</summary>
                    <p class="content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                        ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit
                        in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                        cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                    </p>
                </details>
            </div>
        </article>
        <article class="centered">
            <h4 class="capitalized text-primary hl">Tabs</h4>
            <div class="container tabs-container">
                <div class="tab-header-container">
                    <div class="tab" id="tabOne" v-on:click="openTabOne()">
                        <header class="tab-header">FIRST TAB HEADER</header>
                    </div>
                    <div class="tab" id="tabTwo" v-on:click="openTabTwo()">
                        <header class="tab-header">SECOND TAB HEADER</header>
                    </div>
                    <div class="tab" id="tabThree" v-on:click="openTabThree()">
                        <header class="tab-header">THIRD TAB HEADER</header>
                    </div>
                </div>
                <div class="tab-content-container">
                    <div class="tab-content" id="tcOne">
                        <p>
                            Integer vel arcu ac dolor tincidunt dapibus. Nam sit amet lacinia velit. Pellentesque vel
                            urna diam.
                            Nunc sit amet justo malesuada, tincidunt massa eu, placerat est. Suspendisse commodo
                            pellentesque
                            gravida. Donec suscipit vulputate odio, at eleifend purus condimentum in. Praesent sed
                            cursus sem.
                            Donec mattis urna efficitur diam sagittis, id maximus orci dictum. Etiam non congue felis,
                            et varius
                            augue. Aliquam et ullamcorper massa. Nullam interdum lobortis volutpat. Etiam leo arcu,
                            vulputate
                            vel commodo sit amet, ullamcorper varius dui.
                        </p>
                    </div>
                    <div class="tab-content" id="tcTwo">
                        <p>
                            Quisqe a turpis fermentum, dapibus mauris quis, dignissim ligula. Aliquam aliquet tellus
                            nunc, non
                            fermentum leo dictum vel. Morbi vehicula laoreet felis ac blandit. Sed mi urna, feugiat nec
                            rhoncus
                            vitae, sollicitudin non dui. Vestibulum in porttitor urna, ut posuere elit. Suspendisse mi
                            magna,
                            molestie nec aliquam id, porttitor in ante. Nullam posuere ipsum odio, at placerat ante
                            eleifend
                            vitae. Suspendisse vestibulum magna pretium velit venenatis venenatis. Donec dapibus, justo
                            ut
                            aliquam varius, quam tortor dignissim tellus, imperdiet scelerisque risus ex ac magna. Nunc
                            sed
                            purus nibh. Phasellus elit erat, scelerisque sed volutpat non, interdum vitae urna.
                        </p>
                    </div>
                    <div class="tab-content" id="tcThree">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nibh arcu, ultricies nec
                            purus quis,
                            consequat luctus orci. Sed non mi nisi. Donec vulputate erat odio, eget lacinia lectus
                            accumsan sed.
                            Phasellus diam lorem, ullamcorper quis velit a, ultricies facilisis turpis. Sed laoreet
                            efficitur
                            odio, ut consequat arcu iaculis non. Quisque lectus ligula, venenatis quis ullamcorper
                            vitae,
                            euismod in nisi. Sed sed arcu tortor. Phasellus a iaculis metus, sed suscipit dui. Nunc
                            mollis,
                            ipsum at tristique dignissim, enim mi sodales nulla, sed dapibus lorem tortor et nisi.
                        </p>
                    </div>
                </div>
                <div class="tab-header-container-mobile">
                    <details class="tab">
                        <summary class="inside">FIT GUIDE</summary>
                        <p class="tab-content" id="tcOneMobile">
                            Integer vel arcu ac dolor tincidunt dapibus. Nam sit
                            amet
                            lacinia velit. Pellentesque vel urna diam. Nunc sit amet justo malesuada, tincidunt massa
                            eu,
                            placerat est. Suspendisse commodo pellentesque gravida. Donec suscipit vulputate odio, at
                            eleifend
                            purus condimentum in. Praesent sed cursus sem. Donec mattis urna efficitur diam sagittis, id
                            maximus
                            orci dictum. Etiam non congue felis, et varius augue. Aliquam et ullamcorper massa. Nullam
                            interdum
                            lobortis volutpat. Etiam leo arcu, vulputate vel commodo sit amet, ullamcorper varius dui.
                        </p>
                    </details>
                    <details class="tab">
                        <summary class="inside">CARE</summary>
                        <p class="tab-content" id="tcTwoMobile">
                            Quisqe a turpis fermentum, dapibus mauris quis,
                            dignissim
                            ligula. Aliquam aliquet tellus nunc, non fermentum leo dictum vel. Morbi vehicula laoreet
                            felis ac
                            blandit. Sed mi urna, feugiat nec rhoncus vitae, sollicitudin non dui. Vestibulum in
                            porttitor urna,
                            ut posuere elit. Suspendisse mi magna, molestie nec aliquam id, porttitor in ante. Nullam
                            posuere
                            ipsum odio, at placerat ante eleifend vitae. Suspendisse vestibulum magna pretium velit
                            venenatis
                            venenatis. Donec dapibus, justo ut aliquam varius, quam tortor dignissim tellus, imperdiet
                            scelerisque risus ex ac magna. Nunc sed purus nibh. Phasellus elit erat, scelerisque sed
                            volutpat
                            non, interdum vitae urna.
                        </p>
                    </details>
                    <details class="tab">
                        <summary class="inside">MATERIALS</summary>
                        <div class="tab-content" id="tcThreeMobile">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nibh arcu, ultricies nec
                                purus
                                quis, consequat luctus orci. Sed non mi nisi. Donec vulputate erat odio, eget lacinia
                                lectus
                                accumsan sed. Phasellus diam lorem, ullamcorper quis velit a, ultricies facilisis
                                turpis. Sed
                                laoreet efficitur odio, ut consequat arcu iaculis non. Quisque lectus ligula, venenatis
                                quis
                                ullamcorper vitae, euismod in nisi. Sed sed arcu tortor. Phasellus a iaculis metus, sed
                                suscipit
                                dui. Nunc mollis, ipsum at tristique dignissim, enim mi sodales nulla, sed dapibus lorem
                                tortor
                                et nisi.
                            </p>
                        </div>
                    </details>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4 class="capitalized text-primary hl">Alerts</h4>
            <div class="container">
                <div class="alert">
                    <i class="bx bxs-bell-ring"></i>
                    Primary alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert">
                    <i class="bx bxs-bell-ring"></i>
                    Primary alert with double icons and button
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                    <footer>
                        <button class="outlined" title="">Learn More</button>
                    </footer>
                </div>
                <div class="alert alert--primary">
                    <i class="bx bxs-bell-ring"></i>
                    Primary alert with double icons and button
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                    <p class="content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                        ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit
                        in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                        cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                    </p>
                    <footer>
                        <button class="outlined" title="">Learn More</button>
                    </footer>
                </div>
                <div class="alert alert--info text-primary">
                    <i class="bx bxs-error-circle"></i>
                    Info alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--info text-primary bg-primary-20">
                    <i class="bx bxs-error-circle"></i>
                    Info alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--success text-success">
                    <i class="bx bx-check-circle"></i>
                    Success alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--success text-success bg-success-20">
                    <i class="bx bx-check-circle"></i>
                    Success alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--danger text-danger">
                    <i class="bx bxs-error-alt"></i>
                    Danger alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--danger text-danger bg-danger-20">
                    <i class="bx bxs-error-alt"></i>
                    Danger alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--warn text-warn">
                    <i class="bx bxs-error"></i>
                    Warn alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--warn text-warn bg-warn-20">
                    <i class="bx bxs-error"></i>
                    Warn alert with double icons
                    <button class="is-icon">
                        <i class="bx bx-x"></i>
                    </button>
                </div>
                <div class="alert alert--gradient border-gradient">
                    <i class="bx bxs-magic-wand text-gradient"></i>
                    <span class="text-gradient">Gradient alert with double icons</span>
                    <button class="is-icon">
                        <i class="bx bx-x text-gradient"></i>
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Avatars</h4>
            <div class="container">
                <div>
                    <p class="text-light">Icon not Circle</p>
                    <button class="avatar" title="">
                        <i class="bx bx-user bx-sm"></i>
                    </button>
                </div>
                <div>
                    <p class="text-light">Icon</p>
                    <button class="avatar circle" title="">
                        <i class="bx bx-user bx-sm"></i>
                    </button>
                </div>
                <div>
                    <p class="text-light">Initials</p>
                    <button class="avatar circle" title="">
                        <span>JD</span>
                    </button>
                </div>
                <div>
                    <p class="text-light">Image not Circle</p>
                    <button class="avatar has-image" title="">
                    </button>
                </div>
                <div>
                    <p class="text-light">Idle Status</p>
                    <button class="avatar has-image circle" title="">
                        <div class="status-dot idle"></div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Active Status not Circle</p>
                    <button class="avatar has-image" title="">
                        <div class="status-dot active"></div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Active Status Shaped with Border</p>
                    <button class="avatar has-image shaped border-success" title="">
                        <div class="status-dot active"></div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Active Status</p>
                    <button class="avatar has-image circle" title="">
                        <div class="status-dot active"></div>
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Chips</h4>
            <div class="container">
                <div>
                    <p class="text-light">Text + Colors</p>
                    <button class="sm chip" title="">Chips</button>
                    <button class="sm chip text-primary" title="">Chips</button>
                    <button class="sm chip text-success" title="">Chips</button>
                    <button class="sm chip text-danger" title="">Chips</button>
                    <button class="sm chip text-warn" title="">Chips</button>
                    <button class="sm chip text-dark" title="">Chips</button>
                </div>
                <div>
                    <p class="text-light">Primary Icon</p>
                    <button class="sm chip has-icon bg-primary" title="">
                        <i class="bx bx-message"></i>
                        Chips
                    </button>
                </div>
                <div>
                    <p class="text-light">Dismissable</p>
                    <button class="sm chip" title="">
                        Chips
                        <i class="bx bx-x dbl"></i>
                    </button>
                </div>
                <div>
                    <p class="text-light">Colored</p>
                    <button class="sm chip has-icon bg-primary" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-success" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-danger" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-warn" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-dark" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-light text-dark" title="">
                        Chips
                    </button>
                    <button class="sm chip has-icon bg-dark" title="">
                        <span class="text-gradient">Chips</span>
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Tooltips</h4>
            <div class="container">
                <div>
                    <span class="text-sm tooltips lft" title="" data-text="Tooltip Text Here!">
                        Left Tooltip
                    </span>
                </div>
                <div>
                    <span class="text-sm tooltips rght" title="" data-text="Tooltip Text Here!">
                        Right Tooltip
                    </span>
                </div>
                <div>
                    <span class="text-sm tooltips top" title="" data-text="Tooltip Text Here!">
                        Top Tooltip
                    </span>
                </div>
                <div>
                    <span class="text-sm tooltips btm" title="" data-text="Tooltip Text Here!">
                        Bottom Tooltip
                    </span>
                </div>
                <div>
                    <span class="tooltips lft has-icon" data-text="Hello World!">
                        <button class="is-icon" title="">
                            <i class="bx bx-info-circle"></i>
                        </button>
                    </span>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Badges</h4>
            <div class="container">
                <div>
                    <button class="sm chip bg-primary badge" title="">
                        Primary
                    </button>
                    <button class="sm chip bg-success badge" title="">
                        Success
                    </button>
                    <button class="sm chip bg-warn badge" title="">
                        Warning
                    </button>
                    <button class="sm chip bg-danger badge" title="">
                        Danger
                    </button>
                    <button class="sm chip bg-dark badge" title="">
                        Reminder
                    </button>
                    <button class="sm chip bg-light badge text-dark" title="">
                        Misc
                    </button>
                    <button class="sm chip bg-primary bg-lighten-5 badge" title="">
                        Unavailable
                    </button>
                    <button class="sm chip badge" title="">
                        Offline
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Notifications</h4>
            <div class="container">
                <div>
                    <p class="text-light">Notification</p>
                    <button class="is-icon sm notifiable" title="">
                        <i class="bx bx-envelope"></i>
                        <div class="notice"></div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Notification Single</p>
                    <button class="is-icon sm notifiable" title="">
                        <i class="bx bx-envelope"></i>
                        <div class="notice">2</div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Notification Double</p>
                    <button class="is-icon sm notifiable" title="">
                        <i class="bx bx-envelope"></i>
                        <div class="notice">24</div>
                    </button>
                </div>
                <div>
                    <p class="text-light">Notification Max with Tooltip</p>
                    <button class="is-icon sm notifiable tip tooltip" title="">
                        <i class="bx bx-envelope"></i>
                        <div class="notice">99+</div>
                    </button>
                    <button class="popover sm tooltip bg-danger" title="">
                        You have unread messages!
                    </button>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Selection Controls</h4>
            <div class="container">
                <div>
                    <p class="text-light">Checkbox</p>
                    <input class="checkbox" type="checkbox" />
                    <br />
                    <input type="checkbox" disabled />
                </div>
                <div>
                    <p class="text-light">Radio</p>
                    <input type="radio" />
                    <br />
                    <input type="radio" disabled />
                </div>
                <div>
                    <p class="text-light">Toggle with Label</p>
                    <label class="toggle">
                        <input class="toggle-checkbox" type="checkbox" />
                        <span class="toggle-switch"></span>
                        <span class="toggle-label">Wi-fi</span>
                    </label><br />
                    <label class="toggle">
                        <input class="toggle-checkbox" type="checkbox" disabled />
                        <span class="toggle-switch"></span>
                    </label>
                </div>
                <div>
                    <p class="text-light">Range with Label</p>
                    <label class="toggle">
                        <input class="range" type="range" />
                        <span class="toggle-label">Range</span>
                    </label>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Cards</h4>
            <div class="grid-container col-3">
                <div class="grid-item card">
                    <div class="card-header has-icon">
                        <i class="bx bx-home"></i>
                        <h4 class="title">Step #1</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt ut labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor.
                    </div>
                    <div classs="card-footer"></div>
                </div>
                <div class="grid-item card">
                    <div class="card-header has-image rounded-image">
                        <img src="https://loremflickr.com/64/64" alt="" />
                        <h4 class="title">STEP #1</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt ut labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor.
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header has-image shifted-image box">
                        <img src="https://loremflickr.com/100/100" alt="" />
                        <h4 class="title">STEP #1</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                        labore et dolore magna aliqua.
                    </div>
                    <div class="card-footer">
                        <button class="primary has-icon" title="">
                            Next
                            <i class="bx bx-chevron-right dbl"></i>
                        </button>
                    </div>
                </div>
            </div>
            <div class="grid-container col-3">
                <div class="grid-item card">
                    <div class="card-header has-full-image">
                        <img src="https://loremflickr.com/460/180" alt="" class="invert" />
                        <h4 class="title">Step #1</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                        labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor.
                    </div>
                    <div class="card-footer">
                    </div>
                </div>
                <div class="grid-item card full-product-image flex-item">
                    <div class="card-header">
                        &nbsp;
                    </div>
                    <div class="card-content">
                    </div>
                    <div class="card-footer glass">
                        <h4>Product Name</h4>
                        <p>$29.99</p>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header is-numbered">
                        <div class="number">1</div>
                        <h4>STEP #1</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                        labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor. Quis enim lobortis
                        scelerisque fermentum dui faucibus in. Diam maecenas sed enim ut sem viverra aliquet. Sed
                        blandit libero volutpat sed cras ornare arcu dui.
                    </div>
                    <div class="card-footer">
                    </div>
                </div>
            </div>
            <div class="grid-container col-3">
                <div class="grid-item card">
                    <div class="card-header has-icon">
                        <i class="bx bx-home icon-inline"></i>
                        <h4>Lorem ipsum dolor sit amet consectetur</h4>
                    </div>
                    <div class="card-content">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                        labore et dolore magna aliqua.
                    </div>
                    <div class="card-footer">
                        <a href="#" target="_blank">See more</a>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header has-image rounded-image no-pad">
                        <img src="https://loremflickr.com/260/260/product" alt="" />
                    </div>
                    <div class="card-content">
                        <h4>Product Name</h4>
                        <i class="bx bxs-star"></i>
                        <i class="bx bxs-star"></i>
                        <i class="bx bxs-star"></i>
                        <i class="bx bxs-star"></i>
                        <i class="bx bxs-star-half"></i>
                        <p>&nbsp;</p>
                        <p>$29.99</p>
                    </div>
                    <div class="card-footer">
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header">
                        <div class="step">
                            <div class="number">1</div>
                            <h4 class="lead capitalize">Step one</h4>
                        </div>
                    </div>
                    <div class="card-content align-bottom">
                        <p class="text-primary lead">Lorem ipsum dolor sit amet.</p>
                    </div>
                </div>
            </div>
            <div class="grid-container col-3">
                <div class="grid-item card">
                    <div class="card-header has-full-image">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                    <div class="card-content align-left">
                        <div class="grid-container col-3">
                            <button class="sm chip bg-primary badge">Badge</button>
                            <span></span>
                            <span>April 14, 2022</span>
                        </div>
                        <h4 class="title text-primary">Sample cards are a great way to jump start your project</h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor. Quis enim lobortis
                            scelerisque fermentum dui faucibus in.
                        </p>
                    </div>
                    <div class="card-footer align-left">
                        <a href="#" target="_blank">Read more</a>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header has-full-image">
                        <img src="https://loremflickr.com/300/350/product" alt="" />
                    </div>
                    <div class="card-content no-pad">
                    </div>
                    <div class="card-footer stack-vertical">
                        <h4>Product Name</h4>
                        <div class="box">
                            <i class="bx bxs-star"></i>
                            <i class="bx bxs-star"></i>
                            <i class="bx bxs-star"></i>
                            <i class="bx bxs-star"></i>
                            <i class="bx bxs-star-half"></i>
                        </div>
                        <p class="box">$29.99</p>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header has-full-image">
                        <div class="card--avatar">
                            <i class="bx bx-user"></i>
                        </div>
                    </div>
                    <div class="card-content align-left">
                        <h4 class="text-primary">John Doe</h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua.
                        </p>
                    </div>
                    <div class="card-footer">
                    </div>
                </div>
            </div>
            <div class="grid-container col-3">
                <div class="grid-item card">
                    <div class="card-header">
                    </div>
                    <div class="card-content align-left">
                        <h4 class="text-primary hl">Sample cards are a great way to jump start your project</h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor. Quis enim lobortis
                            scelerisque fermentum dui faucibus in. Diam maecenas sed enim ut sem viverra aliquet. Sed
                            blandit libero volutpat sed cras ornare arcu dui.
                        </p>
                    </div>
                    <div class="card-footer has-author">
                        <i class="bx bx-user card--avatar"></i>
                        <div>
                            <strong>John Doe</strong>
                            <br />
                            <span>April 12, 2022</span>
                        </div>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header">
                    </div>
                    <div class="card-content align-left">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor. Quis enim lobortis
                            scelerisque fermentum dui faucibus in. Diam maecenas sed enim ut sem viverra aliquet. Sed
                            blandit libero volutpat sed cras ornare arcu dui.
                        </p>
                    </div>
                    <div class="card-footer has-author">
                        <i class="bx bx-user card--avatar"></i>
                        <div>
                            <strong>John Doe</strong>
                            <br />
                            <span class="capitalize">UI Designer</span>
                        </div>
                    </div>
                </div>
                <div class="grid-item card">
                    <div class="card-header">
                    </div>
                    <div class="card-content">
                        <div class="card-avatar">
                            <div class="cube">
                                <div class="side top success color-80"></div>
                                <div class="side left success"></div>
                                <div class="side front success color-60"></div>
                            </div>
                        </div>
                        <h4 class="text-primary">John Doe</h4>
                        <p class="align-left">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                            tempor incididunt ut
                            labore et dolore magna aliqua. Porta lorem mollis aliquam ut porttitor.
                        </p>
                    </div>
                    <div class="card-footer">
                    </div>
                </div>
            </div>
            <div class="grid-container col-3">
                <div class="grid-item card quote">
                    <div class="card-header">
                        <h2><i class="bx bxs-quote-alt-left card--avatar"></i></h2>
                    </div>
                    <div class="card-content">
                        <blockquote>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                            incididunt ut labore et dolore magna aliqua.
                        </blockquote>
                    </div>
                    <div class="card-footer container">
                        <h4 class="text-primary">John Doe | CEO</h4>
                        <span class="capitalize">UI Designer</span>
                    </div>
                </div>
                <div class="grid-item card quote bg-primary">
                    <div class="card-header">
                        <i class="bx bx-user card--avatar bg-dark-40"></i>
                    </div>
                    <div class="card-content">
                        <h4>John Doe | CEO</h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua.
                        </p>
                    </div>
                    <div class="card-footer">
                        <div class="socials">
                            <i class="bx bxl-facebook-square bx-lg"></i>
                            <i class="bx bxl-linkedin-square bx-lg"></i>
                            <i class="bx bxl-twitter bx-lg"></i>
                        </div>
                    </div>
                </div>
                <div class="grid-item card bg-rose bg-lighten-2 text-light">
                    <div class="card-header">
                        <i class="bx bx-pulse card--avatar bg-danger text-light circle bx-burst"></i>
                    </div>
                    <div class="card-content align-bottom text-light">
                        <h4>John Doe</h4>
                        <p>CEO of the best company</p>
                    </div>
                    <div class="card-footer">
                        <div class="socials">
                            <i class="bx bxl-facebook-square bx-lg"></i>
                            <i class="bx bxl-linkedin-square bx-lg"></i>
                            <i class="bx bxl-twitter bx-lg"></i>
                        </div>
                    </div>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Slideshow</h4>
            <div class="slideshow">
                <div class="slides">
                    <input type="radio" name="r" id="r1" checked />
                    <input type="radio" name="r" id="r2" />
                    <input type="radio" name="r" id="r3" />
                    <input type="radio" name="r" id="r4" />
                    <input type="radio" name="r" id="r5" />
                    <div class="slide s1">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                    <div class="slide s2">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                    <div class="slide s3">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                    <div class="slide s4">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                    <div class="slide s5">
                        <img src="https://loremflickr.com/460/150/landscape" alt="" />
                    </div>
                </div>
                <div class="ss-navigation glass">
                    <label for="r1" class="bar">&nbsp;</label>
                    <label for="r2" class="bar">&nbsp;</label>
                    <label for="r3" class="bar">&nbsp;</label>
                    <label for="r4" class="bar">&nbsp;</label>
                    <label for="r5" class="bar">&nbsp;</label>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Dropdown Menu</h4>
            <div class="container">
                <nav class="dropdown">
                    <ul>
                        <li class="menu-main">
                            <a href="#">Menu Item One</a>
                            <ul class="sub-menu">
                                <li><a href="#">Sub Item One</a></li>
                                <li><a href="#">Sub Item Two</a></li>
                                <li><a href="#">Sub Item Three</a></li>
                            </ul>
                        </li>
                        <li class="menu-main">
                            <a href="#">Menu Item Two</a>
                            <ul class="sub-menu">
                                <li><a href="#">Sub Item One</a></li>
                                <li><a href="#">Sub Item Two</a></li>
                            </ul>
                        </li>
                        <li><a href="#">Menu Item Three</a></li>
                        <li><a href="#">Menu Item Four</a></li>
                    </ul>
                </nav>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Forms</h4>
            <div class="container">
                <div>
                    <p class="text-light">Text</p>
                    <input type="text" placeholder="Type Something" />
                </div>
                <div>
                    <p class="text-light">Labeled</p>
                    <label class="input-text-label">Label</label>
                    <br />
                    <input type="text" placeholder="Type Something" />
                </div>
                <div>
                    <p class="text-light">Left Icon</p>
                    <input type="text" placeholder="Type Something" class="has-icon" />
                </div>
                <div>
                    <p class="text-light">Right Icon</p>
                    <input type="text" placeholder="Type Something" class="has-icon-right" />
                </div>
                <div>
                    <p class="text-light">Disabled</p>
                    <input type="text" placeholder="Not Eligible" disabled />
                </div>
                <div>
                    <p class="text-light">
                        Resizable Textarea
                    </p>
                    <textarea contenteditable="true"
                              placeholder="Long or multiple lines input can be enabled by using this component. This text field can be filled with two or more lines, so that you can input longer text."></textarea>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Modal</h4>
            <Modal>
                <template v-slot:modal-header>
                </template>
                <template v-slot:modal-content>
                </template>
                <template v-slot:modal-footer>
                </template>
            </Modal>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Navigation</h4>
            <h5>Headers</h5>
            <div class="container">
                <div class="topbar border-dark">
                    <div class="tb-left">
                        <i class="bx bx-menu"></i>
                        Darksight
                    </div>
                    <div class="tb-mid">
                        <div class="tb-container">
                            <div class="tb">Home</div>
                            <div class="tb">Product</div>
                            <div class="tb">Updates</div>
                            <div class="tb">Pricing</div>
                        </div>
                    </div>
                    <div class="tb-right">
                        <button class="outlined">
                            <i class="bx bx-menu"></i>
                            Login
                        </button>
                    </div>
                </div>
                <p>&nbsp;</p>
                <div class="topbar border-dark">
                    <div class="tb-left">
                        <i class="bx bx-menu"></i>
                        <h4 class="text-primary">DARKSIGHT</h4>
                    </div>
                    <div class="tb-mid">
                        <input type="search" placeholder="Search Something" />
                    </div>
                    <div class="tb-right container">
                        <button class="is-icon outlined">
                            <i class="bx bx-home"></i>
                        </button>
                        <button class="is-icon outlined">
                            <i class="bx bx-bell"></i>
                        </button>
                        <button class="is-icon outlined">
                            <i class="bx bx-message"></i>
                        </button>
                        <button class="is-icon avatar has-image outlined" title=""></button>
                    </div>
                </div>
            </div>
            <p>&nbsp;</p>
            <h5>Footers</h5>
            <div class="main-footer">
                <div class="container">
                    <div class="container">
                        <h4 class="text-primary capitalize">Darksight</h4>
                    </div>
                    <div>
                        <p>Home</p>
                        <p>Products</p>
                        <p>Updates</p>
                        <p>Community</p>
                    </div>
                    <div>
                        <p>Blog</p>
                        <p>Terms &amp; Conditions</p>
                        <p>Privacy Policy</p>
                        <p>Sitemap</p>
                    </div>
                    <div>
                        <h5 class="text-light">Weekly Newsletter</h5>
                        <p>Get new updates directly to your inbox.</p>
                        <input type="text" placeholder="your@email.com" />
                        <div>&nbsp;</div>
                        <button class="primary">Subscribe</button>
                    </div>
                </div>
                <div class="container bg-dark copy">
                    <div>
                        <p>&copy; 2022 - All Rights Reserved</p>
                    </div>
                    <div>
                        <p class="socials text-white">
                            <button class="is-icon primary">
                                <i class="bx bxl-twitter"></i>
                            </button>
                            <button class="is-icon primary">
                                <i class="bx bxl-facebook-square"></i>
                            </button>
                            <button class="is-icon primary">
                                <i class="bx bxl-github"></i>
                            </button>
                            <button class="is-icon primary">
                                <i class="bx bxl-youtube"></i>
                            </button>
                        </p>
                    </div>
                </div>
            </div>
        </article>
        <article class="centered">
            <h4>&nbsp;</h4>
            <h4 class="capitalized text-primary hl">Tables</h4>
            <h5>Table Examples</h5>
            <table>
                <thead>
                    <tr>
                        <td>Staff Name</td>
                        <td>Email</td>
                        <td>Last Seen</td>
                        <td>Active Rate</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Merrile Burgett</td>
                        <td class="text-light">shaffei@mac.com</td>
                        <td>2020-08-21</td>
                        <td>98.75%</td>
                    </tr>
                    <tr>
                        <td>Constanza Mariano</td>
                        <td class="text-light">carcus@aol.com</td>
                        <td>2020-05-01</td>
                        <td>90.62%</td>
                    </tr>
                </tbody>
            </table>
            <p>&nbsp;</p>
            <table class="bg-primary bg-lighten-1">
                <thead>
                    <tr>
                        <td>Staff Name</td>
                        <td>Email</td>
                        <td>Last Seen</td>
                        <td>Active Rate</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Merrile Burgett</td>
                        <td class="text-light">shaffei@mac.com</td>
                        <td>2020-08-21</td>
                        <td>98.75%</td>
                    </tr>
                    <tr>
                        <td>Constanza Mariano</td>
                        <td class="text-light">carcus@aol.com</td>
                        <td>2020-05-01</td>
                        <td>90.62%</td>
                    </tr>
                </tbody>
            </table>
        </article>
    </section>
</template>

<script>
    export default {
        methods: {
            /*  openTab function
                -creates variables for each tab and tab content
                -checks if tab content is block and adds is-active style to tab
                -makes tab content visible (block) and adds is-active style to tab
                -also hides the display of other tab content and removes is-active style from other tabs
                -currently 3 separate functions that could probably be one nested function
            */
            openTabOne() {
                var x = document.getElementById("tcOne");
                var y = document.getElementById("tcTwo");
                var z = document.getElementById("tcThree");
                var xd = document.getElementById("tabOne");
                var yd = document.getElementById("tabTwo");
                var zd = document.getElementById("tabThree");
                if (x.style.display === "block",
                    xd.classList.remove("is-active")) {
                    x.style.display = "none";
                } else {
                    x.style.display = "block";
                    xd.classList.add("is-active");
                    y.style.display = "none";
                    yd.classList.remove("is-active");
                    z.style.display = "none";
                    zd.classList.remove("is-active");
                }
            },
            openTabTwo() {
                var x = document.getElementById("tcOne");
                var y = document.getElementById("tcTwo");
                var z = document.getElementById("tcThree");
                var xd = document.getElementById("tabOne");
                var yd = document.getElementById("tabTwo");
                var zd = document.getElementById("tabThree");
                if (y.style.display === "block",
                    yd.classList.remove("is-active")) {
                    y.style.display = "none";
                } else {
                    x.style.display = "none";
                    xd.classList.remove("is-active");
                    y.style.display = "block";
                    yd.classList.add("is-active");
                    z.style.display = "none";
                    zd.classList.remove("is-active");
                }
            },
            openTabThree() {
                var x = document.getElementById("tcOne");
                var y = document.getElementById("tcTwo");
                var z = document.getElementById("tcThree");
                var xd = document.getElementById("tabOne");
                var yd = document.getElementById("tabTwo");
                var zd = document.getElementById("tabThree");
                if (z.style.display === "block",
                    zd.classList.remove("is-active")) {
                    z.style.display = "none";
                } else {
                    x.style.display = "none";
                    xd.classList.remove("is-active");
                    y.style.display = "none";
                    yd.classList.remove("is-active");
                    z.style.display = "block";
                    zd.classList.add("is-active");
                }
            }
        }
    }
</script>

<style scoped>
    .tabs-container {
        display: flex;
        flex-flow: column nowrap;
        margin: 1em auto;
        max-width: 100%;
        justify-content: center;
        align-items: center;
        align-content: center
    }

    .tab-header-container {
        display: flex;
        flex-flow: row nowrap;
        justify-content: space-evenly;
        align-items: center;
        align-content: center;
        text-align: center;
        width: calc(100% - 2em);
        z-index: 100;
    }

    .tab {
        flex: 1 1 auto;
        border: 1px solid var(--primary);
        padding: 0.75rem 2rem;
        letter-spacing: 0.125em;
        transition: background 500ms ease-in-out;
        cursor: pointer;
        width: 33%
    }

        .tab:first-child {
            border-right: 0
        }

        .tab:last-child {
            border-left: 0
        }

        .tab:hover {
            background: var(--primary-60);
        }

        .tab.is-active {
            background: var(--primary-80);
            color: var(--light);
        }

    .tab-content-container {
        display: flex;
        flex-flow: row nowrap;
        justify-content: space-evenly;
        align-items: center;
        align-content: center;
        text-align: center;
        margin: 0 !important;
        max-width: calc(100% - 2em);
        z-index: 2;
    }

    .tab-content {
        color: var(--light-60);
        display: flex;
        background: var(--bg);
        animation: dropIn .5s ease-in-out
    }

        .tab-content,
        .tab-content > p {
            padding: 1em !important;
            font-family: inherit !important;
            letter-spacing: normal !important;
        }

    #tcOne,
    #tcTwo,
    #tcThree {
        /* hides until openTab function changes style.display */
        display: none
    }

    .tab-header-container-mobile {
        /* hides until mobile breakpoint */
        display: none
    }

        .tab-header-container-mobile > .tab {
            border: none !important;
            background: var(--bg) !important;
        }

        .tab-header-container-mobile > details[open] {
            margin-bottom: 1em;
        }

        .tab-header-container-mobile > .tab > .tab-content {
            color: var(--light-60) !important;
            padding: 1em !important;
            text-align: left !important;
        }

    @media (max-width: 768px) {
        .tabs-content-container {
            margin: 0 0 !important;
            padding: 0 !important;
            width: 100vw !important
        }

        .tab-header-container {
            /* hides on mobile */
            display: none;
        }

        .tab-header-container-mobile {
            /* shows only on mobile break */
            display: flex !important;
            flex-flow: row wrap !important;
        }

        .tab {
            display: flex;
            flex-flow: row nowrap;
            width: 100% !important;
            text-align: left;
            align-items: center;
            vertical-align: middle;
            padding: 0 !important;
        }

        .tab-header-container-mobile {
            padding: 1em !important;
        }

        .tab-content-container {
            /* hides on mobile */
            display: none
        }
    }
</style>
