<script>
    import boxcard from './boxcard.vue';

    export default {
        name: 'boxmain',
        components: {
            boxcard
        }
    }

</script>

<template>
    <main class="bg-black">
        <section>
            <div class="container">
                <div class="row">
                    <div class="col ms-main-col">
                        <div class="col">
                            <boxcard></boxcard>
                        </div>

                        <div class="col">
                            <boxcard></boxcard>
                        </div>

                        <div class="col">
                            <boxcard></boxcard>
                        </div>
                        
                        <div class="col">
                            <boxcard></boxcard>
                        </div>

                        
                    </div>
                </div>
            </div>
        </section>

        <section class="ms-blue-box d-flex align-items-center">
            <div class="container">
                <div class="row ms-main-col-blue-area py-3">
                    <div class="ms-img">
                        <div class="col d-flex justify-content-center align-items-center">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics" class="ms-0">
                            <span class="text-white fw-bold">DIGITAL COMICS</span>
                        </div>

                        <div class="col d-flex justify-content-center align-items-center">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="merch-comics">
                            <span class="text-white fw-bold">DC MERCHANDISE</span>
                        </div>

                        <div class="col d-flex justify-content-center align-items-center">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="sub-comics">
                            <span class="text-white fw-bold">SUBSCRIPTION</span>
                        </div>

                        <div class="col d-flex justify-content-center align-items-center">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-comics" class="ms-shop-img">
                            <span class="text-white fw-bold">COMIC SHOP LOCATOR</span>
                        </div>

                        <div class="col d-flex justify-content-center align-items-center">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="shop-comics">
                            <span class="text-white fw-bold">DC POWER VISA</span>
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
                margin: 0 10px 0 10px;
                width: 50px;
            }

            span {
                font-size: 14px;
            }

            .ms-shop-img {
                width: 30px;
            }
        }
    }
}


.ms-main-col {
    height: 160px;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    flex-shrink: 0;
    span {
        font-size: 23px;
    }
}

</style>