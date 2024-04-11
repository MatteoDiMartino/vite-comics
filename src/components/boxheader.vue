<script>

export default {
    name: 'boxheader'
}

</script>

<template>

<header class="bg-white d-flex justify-content-center fs-2 fw-bold">
    <div class="container">
        <div class="row">
            <div class="col ms-box1header">
                <img src="../assets/img/dc-logo.png" alt="dc-logo" class="py-2">
            </div>
            <div class="col ms-box2header d-flex justify-content-end align-items-center">
                <ul>
                    <li>
                        <a href="#">CHARACTERS</a>
                    </li>

                    <li>
                        <a href="#">COMICS</a>
                    </li>

                    <li>
                        <a href="#">MOVIES</a>
                    </li>

                    <li>
                        <a href="#">TV</a>
                    </li>

                    <li>
                        <a href="#">GAMES</a>
                    </li>

                    <li>
                        <a href="#">COLLECTIBLES</a>
                    </li>

                    <li>
                        <a href="#">VIDEOS</a>
                    </li>

                    <li>
                        <a href="#">FANS</a>
                    </li>

                    <li>
                        <a href="#">NEWS</a>
                    </li>

                    <li>
                        <a href="#">SHOP</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</header>

</template>

<style scoped lang="scss">

.ms-box1header {

    img {
        width: 90px;
    }

}

.ms-box2header {

    ul {
        display: flex;
        list-style: none;
    }

    li {
        padding-left: 12px;
    }

    a {
        text-decoration: none;
        font-size: 14px;
    }
}

</style>