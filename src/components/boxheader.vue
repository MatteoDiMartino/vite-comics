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
            <div class="col ms-box2header">
                <ul>
                    <li>
                        <a href="#">link</a>
                    </li>

                    <li>
                        <a href="#">link</a>
                    </li>

                    <li>
                        <a href="#">link</a>
                    </li>

                    <li>
                        <a href="#">link</a>
                    </li>

                    <li>
                        <a href="#">link</a>
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

    a {
        text-decoration: none;
        font-size: 18px;
    }
}

</style>