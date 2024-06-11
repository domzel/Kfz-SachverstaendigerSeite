<template>
  <div class="container mx-auto">
    <main class="mt-10 p-5">
      <section class="text-center mb-10">
        <h1 class="text-5xl font-extrabold leading-none tracking-tight text-black mb-4">
          Herzlich Willkommen
        </h1>
        <br />
        <h2 class="text-4xl font-extrabold leading-none tracking-tight text-black mb-4">
          Nach einem Autounfall überlassen Sie nichts dem Zufall
        </h2>
        <br />
        <p class="text-xl text-black mb-6">
          Sie hatten einen <strong>Verkehrsunfall</strong> und brauchen für Ihre Reparaturwerkstatt einen Schadengutachten oder wollen
          die Schadenersatzforderung bei der gegnerischen Versicherung geltend machen? Dann sind Sie bei mir genau richtig! Ich bewerte
          und erstelle professionell ein unabhängiges <strong>Kfz-Unfallgutachten</strong> über den Schaden an Ihrem Fahrzeug auch bei Ihnen
          zu Hause. Hier finden Sie auch eine Übersicht meiner <NuxtLink to="/leistungen" class="text-blue-500"><strong>Leistungen</strong></NuxtLink>.
        </p>
      </section>

      <section class="lg:flex lg:justify-center lg:space-x-8">
        <div class="card card-compact w-96 bg-white shadow-xl mb-10">
          <figure>
            <img src="/images/startseiteFotoDamian.jpg" alt="Damian Zelder" />
          </figure>
          <div class="card-body text-center">
            <h3 class="card-title text-2xl text-black"><strong>Kontakt</strong></h3>
            <br />
            <div class="w-8 h-8 items-center justify-center">
              <img src="/images/telefonIcon.png" alt="Telefon Icon"  />
            </div>
            <p class="text-xl text-black mt-1">Telefon: 02104/5043939</p>
            <div class="w-8 h-8 items-center justify-center">
              <img src="/images/handyIcon.png" alt="Handy Icon" />
            </div>
            <p class="text-xl text-black">Mobil: 0172 9999 006</p>
          </div>
        </div>

        <div class="card card-compact w-96 bg-white shadow-xl mb-10">
          <figure>
            <img src="/images/felge.jpg" alt="Felge" />
          </figure>
          <div class="card-body text-center">
            <h3 class="card-title text-2xl text-black"><strong>Bagatellschaden</strong></h3>
            <p class="text-xl text-black">
              Sie hatten einen Unfall und es ist fast nichts zu sehen? Unterschätzen Sie selbst einen
              <NuxtLink to="/bagatellschaden" class="text-blue-500"><strong>Bagatellschaden</strong></NuxtLink> nicht! Die heutigen Fahrzeuge
              werden immer mehr mit Kunststoffteilen verkleidet.
              <NuxtLink to="/bagatellschaden" class="text-blue-500">Weitere Informationen</NuxtLink>
            </p>
          </div>
        </div>

        <div class="card card-compact w-96 bg-white shadow-xl mb-10">
          <figure>
            <img src="/images/airbag.jpg" alt="Airbag" />
          </figure>
          <div class="card-body text-center">
            <h3 class="card-title text-2xl text-black"><strong>Totalschaden</strong></h3>
            <p class="text-xl text-black">
              Wenn der kalkulierte Schaden den Wiederbeschaffungswert des Fahrzeugs übersteigt, besteht immer noch
              die Möglichkeit das Fahrzeug zu reparieren. Fachwerkstätte die über das notwendige Equipment verfügen,
              sind in der Lage Ihr Fahrzeug, selbst bei starken Rahmenschaden, in dem oben genannten 130% Bereich
              fachgerecht zu reparieren.
              <NuxtLink to="/unfall/totalschaden" class="text-blue-500">Weitere Informationen</NuxtLink>
            </p>
          </div>
        </div>

        <div class="card card-compact w-96 bg-white shadow-xl mb-10">
          <figure>
            <img src="/images/autoStartseite.jpg" alt="Auto" />
          </figure>
          <div class="card-body text-center">
            <h3 class="card-title text-2xl text-black"><strong>Beweissicherung</strong></h3>
            <p class="text-xl text-black">
              Nach einem <strong>Autounfall</strong>, bei dem die Schuldfrage noch nicht eindeutig geklärt ist,
              biete ich Ihnen eine <strong>kostenlose</strong> Beweissicherung an. Die entstandenen Schäden werden fotografiert und
              als Beweismittel bis zur Klärung der Schuldfrage archiviert.
              <NuxtLink to="/beweissicherung" class="text-blue-500">Weitere Informationen</NuxtLink>
            </p>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup>
definePageMeta({ layout: "default" });
</script>

<style scoped>
.container {
  max-width: 1200px;
}
.header {
  text-align: center;
  padding: 20px;
}
.intro {
  text-align: center;
  padding: 40px;
}
.intro img {
  max-width: 100%;
  height: auto;
  margin-top: 20px;
}
.card-body {
  padding: 20px;
}
</style>
