---
layout: default
title: "Spiludvikling"
permalink: /spiludvikling/
---

# Spiludvikling - mine læringsmål og progressionsbarer 🕹️

_"Are you not entertained? Are you not entertained? Is this not why you are here?" - Maximus Decimus Meridius (Gladiator)_

Her samler jeg alle mine mål for valgfaget **Spiludvikling**. Hvert mål har en enkel **progressionsbar** med 10 felter (0–10 = 0–100%). Jeg opdaterer felterne manuelt hen ad vejen og skriver et blogindlæg, når jeg rykker en bar.

> Baren for hvert mål skifter til grøn efterhånden som jeg arbejder hen imod målet 🎯

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

<!-- 1) FORSTÅ SPILMOTORER -->
<div class="xp">
  <div class="label">Mål 1 — Forstå spilmotorer</div>
  <div class="desc">Jeg kan forklare de grundlæggende principper i en spilmotor (game loop, scenes, assets, scripting, fysik, rendering) og vise det i Unity.</div>

  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 2) BRUG AF UNITY TIL 2D -->
<div class="xp">
  <div class="label">Mål 2 — Brug af Unity til 2D</div>
  <div class="desc">Jeg kan opsætte en 2D-scene i Unity med sprites, physics (Rigidbody2D + Collider2D) og en spilbar figur med inputstyring.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 3) GOD KODE & ARKITEKTUR -->
<div class="xp">
  <div class="label">Mål 3 — God kode & arkitektur</div>
  <div class="desc">Jeg kan strukturere projektet i mapper, bruge prefabs/ScriptableObjects, følge C#-konventioner og lave ≥5 enhedstests der kører uden fejl.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 4) SPILHISTORIE -->
<div class="xp">
  <div class="label">Mål 4 — Spilhistorie</div>
  <div class="desc">Jeg kan skrive en kort narrativ ramme (½–1 side) og præsentere den i spillet (introtekst/dialog) så den skaber stemning og motivation.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 5) GAMEPLAY & LEVEL DESIGN -->
<div class="xp">
  <div class="label">Mål 5 — Gameplay & level design</div>
  <div class="desc">Jeg kan designe mindst 2 baner, der introducerer udfordringer trinvis, teste dem med 2–3 personer og forbedre designet via feedback.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 6) GRAFIK, LYD & LYS -->
<div class="xp">
  <div class="label">Mål 6 — Grafik, lyd & lys</div>
  <div class="desc">Jeg kan integrere grafik, lyd og lys, så de matcher spillets tema: ≥3 SFX, baggrundsmusik og simple 2D-lys for stemning og læsbarhed.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 7) ENGAGEMENT & FASTHOLDELSE -->
<div class="xp">
  <div class="label">Mål 7 — Engagement & fastholdelse</div>
  <div class="desc">Jeg designer en tydelig core loop (fx “udforsk → kæmp → belønning → videre”), indbygger progression og tester med ≥2 spillere og tilpasser.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 8) PERFORMANCE -->
<div class="xp">
  <div class="label">Mål 8 — Performance</div>
  <div class="desc">Jeg kan måle i Unity Profiler og sikre ~60 FPS i en testscene.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 9) SAMARBEJDE & PRODUKTION -->
<div class="xp">
  <div class="label">Mål 9 — Samarbejde & produktion</div>
  <div class="desc">Jeg deltager aktivt i gruppens Git-workflow, laver meningsfulde commits og deltager i ugentlige demoer.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

<!-- 10) TEST & RELEASE -->
<div class="xp">
  <div class="label">Mål 10 — Test & release</div>
  <div class="desc">Jeg planlægger og gennemfører en playtest (≥2 personer uden for gruppen) og laver en færdig build (fx Windows/WebGL) med README og credits.</div>
  <table><tr>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
    <td class=""></td><td class=""></td><td class=""></td><td class=""></td><td class=""></td>
  </tr></table>
  <div class="meta">0% (0/10)</div>
</div>

# Spiludvikling - dokumentation 📚
