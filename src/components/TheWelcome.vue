<template>
  <div class="pantalla-principal">
    <img class="image" alt="Image" src="image-2.png" />
    <img class="img" alt="Image" src="image-1.png" />
    <header class="header">
      <div class="text-wrapper">K’ peliculon</div>
      <img class="icon-user-avatar" alt="Icon user avatar" src="icon-user-avatar.png" />
      <img class="icon-menu" alt="Icon menu" src="icon-menu.png" />
      <div class="div">Películas</div>
      <div class="text-wrapper-2">Inicio</div>
      <div class="text-wrapper-3">Géneros</div>
      <img class="icon-chevron-down" alt="Icon chevron down" src="icon-chevron-down.png" />
      <img class="icon-chevron-down-2" alt="Icon chevron down" src="image.png" />
    </header>
    <img class="image-2" alt="Image" src="image-3.png" />
    <img class="image-3" alt="Image" src="image-4.png" />
    <img class="image-4" alt="Image" src="image-5.png" />
    <img class="image-5" alt="Image" src="image-6.png" />
    <img class="image-6" alt="Image" src="image-9.png" />
    <img class="image-7" alt="Image" src="image-11.png" />
  </div>
</template>

<script>
export default {
  name: "PantallaPrincipal",
};
</script>

<style>
.pantalla-principal {
  background-color: #000000;
  height: 1024px;
  position: relative;
  width: 1440px;
}

.pantalla-principal .image {
  height: 230px;
  left: 39px;
  object-fit: cover;
  position: absolute;
  top: 582px;
  width: 151px;
}

.pantalla-principal .img {
  height: 225px;
  left: 39px;
  object-fit: cover;
  position: absolute;
  top: 317px;
  width: 151px;
}

.pantalla-principal .header {
  background-color: transparent;
  border: 1px solid;
  border-color: transparent;
  border-radius: 2px;
  height: 114px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  width: 1440px;
}

.pantalla-principal .text-wrapper {
  color: #ffffff;
  font-family: "Oswald-Regular", Helvetica;
  font-size: 48px;
  font-weight: 400;
  height: 71px;
  left: 39px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 21px;
}

.pantalla-principal .icon-user-avatar {
  height: 60px;
  left: 1246px;
  position: absolute;
  top: 27px;
  width: 60px;
}

.pantalla-principal .icon-menu {
  height: 38px;
  left: 1345px;
  position: absolute;
  top: 38px;
  width: 50px;
}

.pantalla-principal .div {
  color: #ffffff;
  font-family: "Oswald-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  height: 36px;
  left: 479px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 38px;
}

.pantalla-principal .text-wrapper-2 {
  color: #ffffff;
  font-family: "Oswald-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  height: 36px;
  left: 355px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 38px;
}

.pantalla-principal .text-wrapper-3 {
  color: #ffffff;
  font-family: "Oswald-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  height: 36px;
  left: 633px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 38px;
}

.pantalla-principal .icon-chevron-down {
  height: 7px;
  left: 566px;
  position: absolute;
  top: 57px;
  width: 12px;
}

.pantalla-principal .icon-chevron-down-2 {
  height: 7px;
  left: 713px;
  position: absolute;
  top: 57px;
  width: 12px;
}

.pantalla-principal .image-2 {
  height: 225px;
  left: 228px;
  object-fit: cover;
  position: absolute;
  top: 317px;
  width: 151px;
}

.pantalla-principal .image-3 {
  height: 230px;
  left: 228px;
  object-fit: cover;
  position: absolute;
  top: 582px;
  width: 151px;
}

.pantalla-principal .image-4 {
  height: 225px;
  left: 417px;
  object-fit: cover;
  position: absolute;
  top: 317px;
  width: 155px;
}

.pantalla-principal .image-5 {
  height: 230px;
  left: 417px;
  object-fit: cover;
  position: absolute;
  top: 582px;
  width: 155px;
}

.pantalla-principal .image-6 {
  height: 224px;
  left: 789px;
  object-fit: cover;
  position: absolute;
  top: 318px;
  width: 159px;
}

.pantalla-principal .image-7 {
  height: 224px;
  left: 986px;
  object-fit: cover;
  position: absolute;
  top: 318px;
  width: 159px;
}
</style>