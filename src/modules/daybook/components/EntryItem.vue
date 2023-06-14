<template>
    <div class="entry-container mb-3 pointer p-2">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-ligth">2021, jueves</span>
        </div>

        <div class="entry-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum, enim deserunt distinctio non quisquam
            aspernatur! Explicabo, nam tenetur reiciendis, amet sit ducimus est incidunt totam aliquam eveniet laborum
            dignissimos. Expedita!
        </div>
    </div>
</template>

<script>
/* eslint-disable no-alert */
export default {

}
    /* eslint-disable no-alert */
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2e3650;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: gray, $amount: 45%);
        transition: 0.2s all ease-in;

    }

    .entry-description {
        font-size: 12px;

    }
}
</style>

