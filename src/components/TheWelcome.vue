<template>
  <div class="pantalla-principal">
    <img class="imagen" alt="Imagen" src="" />
    <img class="imagen" alt="Imagen" src="" />
    <header class="encabezado">
      <div class="texto-envoltura">K' peliculon</div>
      <img class="imagenUrl" alt="Icono usuario avatar" src="./icons/user.png" />
      <img class="icono-menu" alt="Icono menu" src="https://cdn-icons-png.flaticon.com/128/2976/2976215.png" />
      <div class="div">Películas</div>
      <div class="texto-envoltura-2">Inicio</div>
      <div class="texto-envoltura-3">Géneros</div>
      <img class="icono-chevron-abajo" alt="Icono chevron abajo" src="https://www.flaticon.es/icono-gratis/flecha-hacia-abajo-para-navegar_32195" />
      <img class="icono-chevron-abajo-2" alt="Icono chevron abajo" src="https://www.flaticon.es/icono-gratis/flecha-hacia-abajo-para-navegar_32195" />
    </header>
    <img class="peli1" alt="Imagen" src="https://media.themoviedb.org/t/p/w220_and_h330_face/6Dc9mMl083cVpNknWzALCw7JYPH.jpg" />
    <img class="peli2" alt="Imagen" src="https://media.themoviedb.org/t/p/w300_and_h450_bestv2/ApiEfzSkrqS4m1L5a2GwWXzIiAs.jpg" />
    <img class="peli3" alt="Imagen" src="https://media.themoviedb.org/t/p/w220_and_h330_face/zS8BSQdbOesql0EWbs17kPvLoAT.jpg" />
    <img class="peli4" alt="Imagen" src="https://media.themoviedb.org/t/p/w220_and_h330_face/diEeiB2DmZZadHISkg24RO2n0rT.jpg" />
    <img class="peli5" alt="Imagen" src="https://media.themoviedb.org/t/p/w220_and_h330_face/mm1M6CoN2qLy8BpnrmYEVToQHJR.jpg" />
    <img class="peli6" alt="Imagen" src="https://media.themoviedb.org/t/p/w220_and_h330_face/iLa15KURiosRmvtWP6vKqBT11Le.jpg" />

  </div>
</template>

<script>
export default {
  name: "TheWelcome",

  data() {
    return {
      // La ruta relativa de la imagen desde el componente
      imagenUrl: require('@/assets/user.png')
    };
  }
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