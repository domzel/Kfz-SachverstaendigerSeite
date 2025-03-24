<template>
  <section class="container lg:flex mx-auto overflow-hidden p-5">
    <article class="container flex flex-col items-center">
      <h2
          class="mt-6 mb-12 text-4xl font-extrabold leading-none tracking-tight md:text-5xl lg:text-6xl text-center text-black">
        Ihr Recht
      </h2>
      <div class="mb-6 w-full sm:px-16 xl:px-48">
        <div class="bg-white shadow-lg rounded-lg p-6">
          <h3 class="text-xl font-medium text-black mb-4">
            <strong>Kfz-Gutachter Ihres Vertrauens</strong>
          </h3>
          <p class="text-black text-lg lg:text-l font-normal">
            Als Geschädigter haben Sie das Recht, einen eigenen, freien und unabhängigen Sachverständigen Ihrer Wahl
            zur Beweissicherung und Feststellung des Schadenumfangs zu beauftragen. Dies gilt auch für den Fall,
            dass durch den Unfallgegner oder dessen Versicherung bereits ein Gutachter beauftragt wurde. Die
            Kosten für ein Sachverständigengutachten sind erstattungspflichtig und müssen in der Regel von der
            regulierenden Versicherung getragen werden!
          </p>
          <br />
          <p class="text-black text-lg lg:text-l font-normal">
            Aufgrund der Schadenminderungspflicht sollte ein Schadengutachten erst ab einer Schadenhöhe von ca.
            EUR 750,00 (Bagatellschadengrenze) erstellt werden. Unterhalb dieser Grenze ist ein Kostenvoranschlag
            ausreichend. Einem Laien ist es jedoch kaum möglich zu beurteilen, wie hoch der Schaden tatsächlich ist.
          </p>
          <br />
          <p class="text-black text-lg lg:text-l font-normal">
            Wir empfehlen daher immer einen Kfz-Sachverständigen zur Feststellung der Schadenhöhe zu beauftragen.
            Sollte dabei festgestellt werden, dass ein
            <NuxtLink to="/bagatellschaden" class="text-blue-500"><strong>Bagatellschaden</strong></NuxtLink>
            vorliegt, so wird der Kfz-Sachverständige
            auch nur einen Kostenvoranschlag erstellen. Die Kosten hierfür können ebenfalls bei der gegnerischen
            Versicherung geltend gemacht werden.
          </p>
        </div>
      </div>

      <div class="mb-6 w-full sm:px-16 xl:px-48">
        <div class="bg-white shadow-lg rounded-lg p-6">
          <h3 class="text-xl font-medium text-black mb-4">
            <strong>Ersatz der Wertminderung</strong>
          </h3>
          <p class="text-black text-lg lg:text-l font-normal">
            Wenn Ihr Fahrzeug trotz fachgerechter Reparatur an Wert verliert, kann die Versicherung dazu verpflichtet
            werden den anfallenden Verlustbetrag zu ersetzen. Dabei müssen Faktoren wie erforderliche Reparaturkosten,
            Altschäden, Reparaturart, Neupreis, Fahrzeugalter, Laufleistung, Wiederbeschaffungs- / Veräußerungswert,
            Erhaltungszustand sowie die aktuelle Marktlage des Fahrzeuges berücksichtigt werden.
          </p>
          <br />
          <p class="text-black text-lg lg:text-l font-normal">
            Die Prüfung dieser Voraussetzungen und die Berechnung der Höhe der anfallenden Wertminderung ermittelt
            der beauftragte Kfz-Sachverständige. Es liegt auf der Hand, dass ein von der gegnerischen Versicherung
            beauftragter Gutachter auf diesen Punkt ganz gerne verzichtet!
          </p>
        </div>
      </div>

      <div class="mb-6 w-full sm:px-16 xl:px-48">
        <div class="bg-white shadow-lg rounded-lg p-6">
          <h3 class="text-xl font-medium text-black mb-4">
            <strong>Mietwagen oder Nutzungsausfall-Entschädigung</strong>
          </h3>
          <p class="text-black text-lg lg:text-l font-normal">
            Als Geschädigter haben Sie für die nachgewiesene Dauer der Reparatur oder im Falle eines Totalschadens
            für die Dauer der Wiederbeschaffung eines vergleichbaren Fahrzeugs, zumeist einen Anspruch auf einen
            Leihwagen bzw. bei Verzicht auf einen Mietwagen eine Nutzungsausfallentschädigung.
          </p>
          <br />
          <p class="text-black text-lg lg:text-l font-normal">
            Die Höhe des Betrages für die Nutzungsausfallentschädigung richtet sich nach der Fahrzeugkategorie
            und dem Alter des beschädigten Fahrzeuges sowie der Wiederbeschaffungsdauer bzw. der Reparaturdauer.
            Diese wird von dem beauftragten Sachverständigen festgesetzt.
          </p>
        </div>
      </div>

      <div class="mb-6 w-full sm:px-16 xl:px-48">
        <div class="bg-white shadow-lg rounded-lg p-6">
          <h3 class="text-xl font-medium text-black mb-4">
            <strong>Rechtsanwalt Ihres Vertrauens</strong>
          </h3>
          <p class="text-black text-lg lg:text-l font-normal">
            Für eine rechtliche Beratung sowie zur Durchsetzung Ihrer Ansprüche dürfen Sie einen Rechtsanwalt Ihres
            Vertrauens beauftragen, die Gebühren hierfür muss in aller Regel die gegnerische Versicherung tragen.
            Nutzen Sie die Ihnen zustehenden Rechte und achten Sie auf eine vollständige und nicht nur eine schnelle
            Schadenregulierung.
          </p>
          <br />
          <p class="text-black text-lg lg:text-l font-normal">
            Denn neben dem eigentlichen Schaden können durch einen Unfall diverse
            <strong>weitere Ersatzansprüche</strong> entstehen:
          </p>
          <ul class="mt-3 list-disc list-inside text-black text-lg lg:text-l font-normal">
            <li>An- und Abmeldekosten</li>
            <li>Abschleppkosten</li>
            <li>Umbaukosten</li>
            <li>Reparaturbestätigungskosten</li>
            <li>Schmerzensgeld</li>
            <li>Arbeitsausfall</li>
            <li>Arztkosten</li>
            <li>Bergungskosten</li>
            <li>Aufwandspauschalen</li>
            <li>Entsorgungskosten</li>
            <li>Gerichtskosten</li>
            <li>Transportkosten</li>
          </ul>
        </div>
      </div>
    </article>
  </section>
</template>

<script>
export default {
  name: "rechte"
}
</script>

<style scoped>

</style>