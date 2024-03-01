<template>
  <div class="container mx-auto flex flex-col items-center">
    <h1 class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-black md:text-5xl lg:text-6xl text-center dark:text-white">
      Herzlich Willkommen</h1>
    <Slider />
    <br />
    <section class="container lg:flex mx-auto mt-10 p-5">
      <div class="card card-compact w-96 bg-gray-300 shadow-xl">
        <figure>
          <img src="/images/startseiteFotoDamian.jpg" alt="Damian Zelder" />
        </figure>
        <div class="card-body">
          <h3 class="card-title text-xl text-black">Telefon:</h3>
          <p class="text-xl">02104/5043939</p>
          <h3 class="card-title text-xl text-black">Mobil:</h3>
            <p class="text-xl">0172 9999 006</p>
        </div>
      </div>
      <article class="container flex flex-col items-center mt-10">
        <h2
            class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-black md:text-5xl lg:text-6xl text-center">
          Nach einem Autounfall überlassen Sie nichts dem Zufall
        </h2>
        <p class="mb-6 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-300">
          <a>
            Sie hatten einen <strong>Verkehrsunfall</strong> und brauchen für Ihre Reparaturwerkstatt einen Schadengutachten oder wollen
            die Schadenersatzforderung bei der gegnerischen Versicherung geltend machen?
          Dann sind Sie bei mir genau richtig! Ich bewerte und erstelle professionell ein unabhängiges
            <strong>Kfz-Unfallgutachten</strong> über den Schaden an Ihrem Fahrzeug auch bei Ihnen zu Hause.
            Hier finden Sie auch eine Übersicht meiner <NuxtLink to="/leistungen" class="link link-hover"><strong>Leistungen</strong></NuxtLink>.
        </a>
        </p>
      </article>
    </section>

    <section class="container lg:flex mx-auto mt-10 p-5">
      <div class="m-2 p-10">
        <div class="card card-compact w-96 bg-gray-300 shadow-xl">
          <figure>
            <img src="/images/felge.jpg" alt="Felge" class="w-full"/>
          </figure>
          <div class="card-body">
            <h3 class="card-title text-xl text-black">Bagatellschaden</h3>
            <p class="text-xl">
              Sie hatten einen Unfall und es ist fast nichts zu sehen?
              Unterschätzen Sie selbst einen
              <NuxtLink to="/bagatellschaden" class="link link-hover"><strong>Bagatellschaden</strong></NuxtLink>
              nicht!
              Die heutigen Fahrzeuge werden immer mehr mit Kunststoffteilen verkleidet.
              <NuxtLink to="/bagatellschaden" class="link link-hover">Weitere Informationen</NuxtLink>
            </p>
          </div>
        </div>
      </div>
      <div class="m-2 p-10">
      <div class="card card-compact w-96 bg-gray-300 shadow-xl">
        <figure>
          <img src="/images/airbag.jpg" alt="Airbag" class="w-full" />
        </figure>
        <div class="card-body">
          <h3 class="card-title text-xl text-black">Totalschaden</h3>
          <p class="text-xl">
            Wenn der kalkulierte Schaden den Wiederbeschaffungswert des Fahrzeugs übersteigt, besteht immer noch
            die Möglichkeit das Fahrzeug zu reparieren. Fachwerkstätte die über das notwendige Equipment verfügen,
            sind in der Lage Ihr Fahrzeug, selbst bei starken Rahmenschaden, in dem oben genannten 130% Bereich
            fachgerecht zu reparieren.
            <NuxtLink to="/unfall/totalschaden" class="link link-hover">Weitere Informationen</NuxtLink>
          </p>
        </div>
      </div>
      </div>
      <div class="m-2 p-10">
        <div class="card card-compact w-96 bg-gray-300 shadow-xl">
          <figure>
           <img src="/images/autoStartseite.jpg" alt="Felge" class="w-full"/>
          </figure>
          <div class="card-body">
            <h3 class="card-title text-xl text-black">Beweissicherung</h3>
            <p class="text-xl">
              Nach einem <strong>Autounfall</strong>, bei dem die Schuldfrage noch nicht eindeutig geklärt ist,
              biete ich Ihnen eine <strong>kostenlose</strong> Beweissicherung an.
              Die entstandenen Schäden werden fotografiert und als Beweismittel bis zu
              Klärung der Schuldfrage archiviert.
              <NuxtLink to="/beweissicherung" class="link link-hover">Weitere Informationen</NuxtLink>
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import Slider from "~/components/Slider.vue";
definePageMeta( { layout: "default" })
</script>

<style scoped>
h1{
  color: black;
}
p{
  color: black;
  margin: 20px 0;
}
</style>
