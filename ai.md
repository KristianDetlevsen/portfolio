---
layout: default
title: "AI"
permalink: /ai/
---

# AI og machine learning - mine læringsmål og progressionsbarer 🤖

_"Your scientists were so preoccupied with whether or not they could that they didn't stop to think if they should." - Dr. Ian Malcolm (Jurassic Park)_

Her samler jeg alle mine midlertidige mål for valgfaget **AI og machine learning**. Hvert mål har en enkel **progressionsbar** med 10 felter (0–10 = 0–100%). Jeg opdaterer felterne manuelt undervejs og skriver et blogindlæg, når jeg rykker baren.

> Baren for hvert mål skifter til grøn efterhånden som jeg arbejder hen imod målet 🎯

> Under hver bar har jeg desuden lagt dokumentation i form af et billede eller en kort tekst 📄

<style>
/* XP-bar (midnight tema) */
.xp{font:600 .95rem/1.4 system-ui,sans-serif; margin:1.1rem 0}
.xp .label{margin-bottom:.25rem}
.xp .desc{opacity:.9; margin-bottom:.35rem}

.xp table{border-collapse:separate; border-spacing:0; width:100%; max-width:720px; margin:0}
.xp td{
  width:10%; height:24px;
  background:rgba(255,255,255,.10);
  border-right:1px solid rgba(255,255,255,.06);
}
.xp td:first-child{border-top-left-radius:6px; border-bottom-left-radius:6px}
.xp td:last-child{border-right:none; border-top-right-radius:6px; border-bottom-right-radius:6px}
.xp td.filled{background:#22c55e}

/* Meta tekst lige under baren */
.xp .meta{
  opacity:.85; font-weight:600;
  margin-top:.15rem;   /* meget lille luft */
  font-size:.9rem;
  text-align:right;    /* højrejusteret under baren */
}
</style>

<!-- SÅDAN BRUGER DU EN BAR:
     - Læg "class='filled'" på så mange <td> som du vil (0–10).
     - Opdatér teksten i .meta (fx “30% (3/10)”). -->

<!-- 1) GRUNDLÆGGENDE AI/ML -->
<div class="xp">
  <div class="label">Mål 1 — Grundlæggende AI/ML</div>
  <div class="desc">Jeg kan forklare forskellen på AI, Machine Learning og Deep Learning, og nævne mindst 3 typiske algoritmer og deres anvendelser.</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">80% (8/10)</div>
</div>

> Jeg har især fokuseret LLM'er, som benytter neurale netværk til at generere et tekstoutput baseret på brugerinput (prompt). AI er et overordnet begreb, som handler om at få en computer til at efterligne menneskeligt ræsonnement. Machine Learning handler om at få en computer til at genkende mønstre baseret på træningsdata og Deep Learning benytter flere lag til dette.

<!-- 2) PRAKTISK ML-MODEL (C#) -->
<div class="xp">
  <div class="label">Mål 2 — Praktisk ML-model (C#)</div>
  <div class="desc">Jeg kan indsamle og forbehandle et datasæt (fx tekstbaserede brugernavne) samt træne og evaluere en simpel klassifikations- eller regressionsmodel i ML.NET (fx accuracy, precision/recall, confusion matrix).</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
    <td class="filled"></td><td class="filled"></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">70% (7/10)</div>
</div>

<figure style="text-align: center;">
    <img src="{{ '/assets/img/ProfanityCheck.png' | relative_url }}" alt="Ordet 'shit' bliver her evalueret af modellen" width="400">
    <figcaption>Modellen checker her ordet "shit", som den vurderer er upassende med 98% sandsynlighed</figcaption>
</figure>

<!-- 3) INTEGRATION AF AI-SERVICE -->
<div class="xp">
  <div class="label">Mål 3 — Integrere AI-service (Anthropic)</div>
  <div class="desc">Jeg kan bygge en lille app (web eller konsol i C#), der kalder Claude Api og demonstrerer et flow fra input → service → output.</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
  </tr></table>
  <div class="meta">100% (10/10)</div>
</div>

> Her er et link til mit miniprojekt, som jeg er ret stolt af: [ClaudeQuestions projekt](https://github.com/KristianDetlevsen/ClaudeQuestions){:target="\_blank"}

<!-- 4) AI I VIRKSOMHEDER (CASE) -->
<div class="xp">
  <div class="label">Mål 4 — AI i virksomheder (case)</div>
  <div class="desc">Jeg kan analysere en virksomhedscase og beskrive mindst 2 konkrete anvendelser af AI, inkl. værdi, fordele, udfordringer og tekniske krav.</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">50% (5/10)</div>
</div>

> I projektet Mega-Eater anvender vi machine learning til at bestemme hvorvidt et indtastet brugernavn er upassende. Det er en interessant proces, som gør spillet mere interaktivt for spilleren, men det er værd at overveje, om det ikke er mere sikkert bare at lade spilleren vælge en kombination af præfabrikerede navne som f.eks. "Awesome Shark".

<!-- 5) MLOPS-LIGHT -->
<div class="xp">
  <div class="label">Mål 5 — MLOps-light</div>
  <div class="desc">Jeg kan forklare formålet med MLOps og beskrive mindst 3 principper (CI/CD for modeller, data/model-versionering, monitorering), samt skitsere et simpelt pipeline-flow.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

> Dette aspekt af AI nåede jeg ikke at arbejde med.

<!-- 6) ETIK & ANSVARLIGHED -->
<div class="xp">
  <div class="label">Mål 6 — Etik & ansvarlighed</div>
  <div class="desc">Jeg kan identificere mindst 2 etiske problemstillinger (fx bias, GDPR, transparens) i en case og foreslå konkrete afbødninger (fairness-tests, anonymisering, model-forklarbarhed).</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td><td class="filled"></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">50% (5/10)</div>
</div>

> Det bør her nævnes, at de store LLM'er typisk er trænet primært på engelsk og skal derfor bruge flere tokens for at bearbejde tekst på andre sprog. Når der benyttes flere tokens, bliver det dyrere at benytte en LLM's Api.

<!-- 7) IMPLIKATIONER AF AI -->
<div class="xp">
  <div class="label">Mål 7 — Implikationer af AI</div>
  <div class="desc">Jeg kan reflektere over de samfundsmæssige, organisatoriske og personlige implikationer ved at anvende AI (fx ændringer i arbejdsprocesser, kompetencekrav, autenticitet, kreativitet, afhængighed af leverandører) og diskutere mindst 2 fordele og 2 udfordringer i en relevant case.</div>
  <table><tr>
    <td class="filled"></td><td class="filled"></td><td class="filled"></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">30% (3/10)</div>
</div>

> Jeg har igennem hele processen gjort mig mange overvejelser om dette, men jeg har ikke fået struktureret mine overvejelser.
