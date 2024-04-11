<script>

    export default {
        name: 'boxmain'
    }

</script>

<template>
    <main class="bg-black">
        <div class="container">
            <div class="row">
                <div class="col ms-main-col">
                    <span class="text-white fw-bold"> --> Content goes here <-- </span>
                </div>
            </div>
        </div>
    </main>

</template>

<style scoped lang="scss">

.ms-main-col {

    height: 250px;
    display: flex;
    align-items: center;

    span {
        font-size: 23px;
    }
}

</style>