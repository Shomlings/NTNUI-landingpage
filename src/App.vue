<script setup lang="ts">
import Page from "./components/Page.vue";
import BouncingLetters from "./components/BouncingLetters.vue";
</script>

<template>
  <Page nextpage="Admin">
    <br />
    <img class="logo" src="./assets/logo.png" />
    <BouncingLetters />
  </Page>
  <Page page="Admin" nextpage="Idrett">
    <h1>NTNUI Admin</h1>
    <a
      href="https://mediearkiv.ntnui.no/NTNUIAdmin/Adminsamling-vår-2023/i-qQqjfqM/A"
      ><img
        src="https://photos.smugmug.com/photos/i-qQqjfqM/0/M/i-qQqjfqM-M.jpg"
        alt=""
    /></a>
    <p>NTNUI har mange admin utvalg.. blablabla.. gøy å være frivillig</p>
  </Page>
  <Page page="Idrett" nextpage="aktivCampus">
    <h1>Idretter</h1>
    <div class="col">
      <a
        href="https://mediearkiv.ntnui.no/NTNUI-Turn/2022/Midtnorsk-Mesterskap-2022/i-fCkJnXf/A"
        ><img
          src="https://photos.smugmug.com/photos/i-fCkJnXf/0/L/i-fCkJnXf-L.jpg"
          alt=""
      /></a>
      <p>
        NTNUI er Norges teknisk og naturvitenskapelige universitets
        idrettsforening og har siden 1910 stått for universitetets sportslige
        tilbud. I motsetning til studentidrettslag i andre land, driftes NTNUI
        utelukkende av studenter. I dag er NTNUI blitt landets største og mest
        allsidige idrettsforening med nesten 20 000 medlemmer og et tilbud på
        mange flere idretter enn NIF har forbund. «Å få så mange studenter som
        mulig i fysisk aktivitet og fremme kameratslig samvær» – det var NTNUIs
        målsetting da organisasjonen ble stiftet. I dag jobber NTNUI fortsatt
        for et sunt studentmiljø og for at terskelen for å trene ved NTNU holdes
        så lav som mulig.
      </p>
    </div>
  </Page>
  <Page page="aktivCampus" nextpage="Studenterhytta">
    <h1>aktivCampus</h1>
  </Page>
  <Page page="Studenterhytta">
    <h1>Studenterhytta</h1>
  </Page>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Baloo+Thambi+2:wght@600&display=swap");

body {
  background-color: #00813d;
  background-image: url("./assets/background.png");
  background-size: 10%;
  background-attachment: fixed;
}
body {
  -ms-overflow-style: none; /* Internet Explorer 10+ */
  scrollbar-width: none; /* Firefox */
}
body::-webkit-scrollbar {
  display: none; /* Safari and Chrome */
}
html {
  scroll-behavior: smooth;

  overflow-y: scroll;
  scroll-snap-type: y mandatory;
}

.logo {
  max-height: 250px;
  object-fit: contain;
}

.down {
  max-height: 75px;
  cursor: pointer;
  animation: myAnim 3s ease 0s infinite normal forwards;
  transition: 0.2s;
}
.down:hover {
  animation: none;
  scale: 1.3;
  transition: 0.2s;
}

@keyframes myAnim {
  0%,
  50%,
  100% {
    opacity: 1;
  }

  25%,
  75% {
    opacity: 0.4;
  }
}
@keyframes myAnimm {
  0% {
    background-position: 0% 50%;
  }

  100% {
    background-position: 50% 50%;
  }
}
.col {
  flex-direction: column;
  justify-content: space-around;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  gap: 20px;
}
p {
  text-align: initial;
}
.col img {
  max-height: 50vh;
  object-fit: contain;
}
</style>
