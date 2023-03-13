<template>
    <div class="gallery">
        <a class="item" href="https://coffeet0code.github.io/CCL_WS21/Mission%20Siroc/">
            <h1>2D Canvas Game</h1>
            <img class="gallery-item" src="../assets/title.png" alt="">
        </a>
        <a class="item" href="https://coffeet0code.github.io/BCC_CSC_Frogger/">
            <h1>2D Canvas Game</h1>
            <img class="gallery-item" src="https://github.com/coffeeT0code/BCC_CSC_Frogger/blob/master/assets/start_bg.png?raw=true" alt="">
        </a>
        <div class="item">
            <NuxtLink to="/item">
            <h1>Webshop Frontend and Backend Final</h1>
            <img class="gallery-item" src="../assets/shop4.jpg"> 
            </NuxtLink>
        </div>

        <div class="item">
            <h1>Android Native App Rôle</h1>
            <video class="gallery-item" src="../assets/role-demo.mp4" controls></video>
        </div>

        <div class="item figma">
            <h1>Health App</h1>
            <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FKHFGmpUVLE7JlPqs1X7Ubu%2FFinal-Project-Victoria-Loibl%3Fnode-id%3D1%253A20%26t%3DPJz7tqKUsFIlgxru-1" allowfullscreen></iframe>
        </div>

        <div class="item figma">
            <h1>Banking App</h1>
            <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2F7KQCokjBtRk1VJVSTNJyeK%2FLoibl_Victoria_cc211005%3Fnode-id%3D14%253A7%26t%3DrcFCD1M0cw5hdGhq-1" allowfullscreen></iframe>
        </div>

    </div>
</template>

<style>


.gallery {
    position: relative;
    left: 10%;
    display: grid;
    justify-content: center;
    align-items: flex-start;

    margin: 10%;
    margin-top: 50px;
    width: fit-content;
    grid-template-columns: 500px 500px;
    column-gap: 100px;
    row-gap: 100px;
}

.item {
    text-align: center;
}

.figma {
    grid-column: span 2;
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

@media only screen and (max-width: 768px) {
  /* For mobile phones: */
  .gallery {
    grid-template-columns: 500px;

  }

  .figma {
    grid-column: span 1;
}
}

</style>