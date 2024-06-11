<template>
  <section class="container lg:flex mx-auto mt-10 overflow-hidden p-5">
    <article class="container flex flex-col items-center mt-10">
      <h2
          class="mb-4 text-4xl font-extrabold leading-none tracking-tight md:text-5xl lg:text-6xl text-center text-black">
        Mein Service für Sie
      </h2>
      <p class="mb-6 text-lg font-normal text-black lg:text-xl sm:px-16 xl:px-48">
        <div class="collapse bg-white">
          <input type="checkbox" />
          <div class="collapse-title text-xl font-medium text-black">
            KFZ-Schadengutachten ohne Vorauszahlung
          </div>
          <div class="collapse-content">
            <p>
              Es ist egal ob Ihr Fahrzeug auf der Straße oder auf dem Parkplatz beschädigt wurde. Der Verursacher muss
              für den Schaden aufkommen. Für einegenaue Schadenschätzung benötigen Sie professionelle Hilfe.
              Als unabhängiger Kfz Sachverständiger ermittle ich den vollen Schadenumfang.
            </p>
            <p>
              Auch wenn die gegnerische Versicherung Ihnen ein Angebot macht das Fahrzeug zu besichtigen.
              Sie haben das Recht auf einen Kfz-Sachverständigen, Kfz-Gutachter Ihrer Wahl.
            </p>
            <p>
              Im Haftpflichtfall tritt an die Stelle des Unfallverursachers dessen Haftpflichtversicherung.
              <strong>Schadenersatzansprüche</strong> wie <strong>Reparaturkosten</strong>, Kosten für einen freien
              und unabhängigen Kfz-Sachverständigen
              oder <strong>rechtlichen Beistand werden von der gegnerischen Versicherung getragen</strong>.
            </p>
          </div>
        </div>
      </p>
      <p class="mb-6 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48">
        <div class="collapse bg-white">
          <input type="checkbox" />
          <div class="collapse-title text-xl font-medium text-black">
            Kostenlose Beweissicherung bei offener Schuldfrage
          </div>
          <div class="collapse-content">
            <p>
              Nach einem <strong>Autounfall</strong>, bei dem die Schuldfrage noch nicht eindeutig geklärt ist,
              biete ich Ihnen eine <strong>kostenlose</strong> Beweissicherung an.
              <img src="/images/autoStartseite.jpg" />
            </p>
            <p>
              Die entstandenen Schäden werden fotografiert und als Beweismittel bis zu Klärung der
              Schuldfrage archiviert.
              Nach dem die Schuldfrage geklärt ist kann anhand der gespeicherten Bilder und Dokumente
              ein <strong>Kfz-Schadengutachten</strong> erstellt werden.
            </p>
          </div>
        </div>
      </p>
    </article>
    <div class="ml-32 pt-10">
      <div class="card card-compact w-96 bg-white shadow-xl">
        <div class="card-body">
          <h3 class="card-title text-xl text-black">Telefon:</h3>
          <p class="text-xl">02104/5043939</p>
          <h3 class="card-title text-xl text-black">Mobil:</h3>
          <p class="text-xl">0172 9999 006</p>
        </div>
        <figure>
          <img src="/images/damianDraussen.jpg" alt="Felge" class="w-full"/>
        </figure>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "leistungen"
}
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