<template>
    <div class="itemView">
        <div class="item">
            <h1>Webshop "Astheatically"</h1>
            <img src="../assets/shop1.jpg" alt="">
            <img src="../assets/shop2.jpg" alt="">
            <img src="../assets/shop3.jpg" alt="">
            <img src="../assets/shop4.jpg" alt="">
            <img src="../assets/shop5.jpg" alt="">
        </div>
    </div>
</template>

<style>
.uxgallery {
    position: relative;
    left: 10%;
    display: grid;
    justify-content: center;
    align-items: flex-start;

    margin: 10%;
    margin-top: 50px;
    width: fit-content;
    grid-template-columns: 500px;

    column-gap: 100px;
    row-gap: 100px;
}

.item {
    text-align: center;
}

.gallery-item {
    width: 500px;
    height: 500px;
    object-fit: contain;
}

a {
    text-decoration: none;
}

h1 {
    padding: none;
    margin: none;
    margin-bottom: 20px;

}

img {
    height: 500px;
    width: auto;
}
</style>