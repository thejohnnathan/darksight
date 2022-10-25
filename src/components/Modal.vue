<script setup>
    function showModal() {
        document.getElementById("dialog").classList.toggle("hide");
    }
    function showModalT() {
        document.getElementById("dialogT").classList.toggle("hide");
    }
    function showModalB() {
        document.getElementById("dialogB").classList.toggle("hide");
    }
    function showModalTR() {
        document.getElementById("dialogTR").classList.toggle("hide");
    }
    function showModalTL() {
        document.getElementById("dialogTL").classList.toggle("hide");
    }
    function showModalBR() {
        document.getElementById("dialogBR").classList.toggle("hide");
    }
    function showModalBL() {
        document.getElementById("dialogBL").classList.toggle("hide");
    }
</script>

<template>
    <div class="grid-container col-5">
        <button class="bg-primary" id="open" @click="showModal()"><i class="bx bx-border-inner"></i></button>
        <button class="bg-primary" id="open" @click="showModalB()"><i class="bx bx-border-bottom"></i></button>
        <button class="bg-primary" id="open" @click="showModalT()"><i class="bx bx-border-top"></i></button>
        <button class="bg-primary" id="open" @click="showModalTR()"><i class="bx bx-border-radius"></i></button>
        <button class="bg-primary" id="open" @click="showModalTL()"><i class="bx bx-border-radius t-l"></i></button>
        <button class="bg-primary" id="open" @click="showModalBR()"><i class="bx bx-border-radius b-r"></i></button>
        <button class="bg-primary" id="open" @click="showModalBL()"><i class="bx bx-border-radius b-l"></i></button>
    </div>
    <dialog open="false" id="dialog" class="glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModal()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogT" class="top glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalT()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogB" class="btm glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalB()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogTR" class="top-right glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalTR()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogTL" class="top-left glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalTL()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogBR" class="bottom-right glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalBR()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
    <dialog open="false" id="dialogBL" class="bottom-left glass">
        <i class="bx bx-x i-inline modal-closable" @click="showModalBL()"></i>
        <div class="modal-header">
            <slot name="modal-header">
                <h4>Dialog Title</h4>
            </slot>
        </div>
        <div class="modal-content">
            <slot name="modal-content">
                <p>Modal content here.</p>
            </slot>
        </div>
        <div class="modal-footer">
            <slot name="modal-footer" class="modal-footer">
                <p>Footer here.</p>
            </slot>
        </div>
    </dialog>
</template>

<style>
    i.b-r {
        transform: rotate(90deg);
    }

    i.t-l {
        transform: rotate(-90deg);
    }

    i.b-l {
        transform: rotate(-180deg);
    }
</style>