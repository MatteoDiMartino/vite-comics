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
                    <div class="ms-main-col-blue-area col py-3">
                        <div class="d-flex ms-img align-items-center">
                            <div>
                                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                                <span class="text-white fw-bold">DIGITAL COMICS</span>
                            </div>

                            <div>
                                <img src="../assets/img/buy-comics-merchandise.png" alt="merch-comics">
                                <span class="text-white fw-bold">DC MERCHANDISE</span>
                            </div>

                            <div>
                                <img src="../assets/img/buy-comics-subscriptions.png" alt="sub-comics">
                                <span class="text-white fw-bold">SUBSCRIPTION</span>
                            </div>

                            <div>
                                <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-comics">
                                <span class="text-white fw-bold">COMIC SHOP LOCATOR</span>
                            </div>

                            <div>
                                <img src="../assets/img/buy-dc-power-visa.svg" alt="shop-comics">
                                <span class="text-white fw-bold">DC POWER VISA</span>
                            </div>
                        </div>
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

    .ms-main-col-blue-area  {
        .ms-img {
            display: flex;
            justify-content: center;
            align-items: center;

            img {
                margin: 0 0 0 11px;
                width: 60px;
            }
        }
    }
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