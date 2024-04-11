<script>

    export default {
        name: 'boxmain'
    }

</script>

<template>
    <main class="bg-black">
        <section>
            <div class="container">
                <div class="row">
                    <div class="col ms-main-col">
                        <span class="text-white fw-bold"> --> Content goes here <-- </span>
                    </div>
                </div>
            </div>
        </section>

        <section class="ms-blue-box">
            <div class="container">
                <div class="row">
                    <div class="col">
                        ciao
                    </div>
                </div>
            </div>
        </section>
    </main>

</template>

<style scoped lang="scss">

.ms-blue-box {
    height: 200px;
    background-color: #0282f9;
}


.ms-main-col {
    height: 160px;
    display: flex;
    align-items: center;

    span {
        font-size: 23px;
    }
}

</style>