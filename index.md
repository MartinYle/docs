---
title: Home
layout: home
---

<html>
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.2/anime.min.js"></script>
  <style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

:root {
  --yle-blue-color:             rgb(0, 180, 200);
  --violet-color:               rgb(124, 89, 250);
  --deep-blue-color:            rgb(19, 22, 37);
  --deep-blue-alpha-color:      rgba(19, 22, 37, 0.8);
  --deep-blue-alpha-less-color: rgba(19, 22, 37, 0.6);
  --black-color:                rgb(0, 0, 0);
  --white-color:                rgb(255, 255, 255);
  --breaking-color:             rgb(233, 14, 67);
}

.main {
  display: flex;
  justify-content: center;
}
.planssi1 {
  display: flex;
  flex-direction: column;
  background: var(--deep-blue-color);
  padding: 1em;
  margin: 1em .25em 1em .25em;
  align-items: right;
  border-radius: 0.2vw;
  font-weight: 700;
  color: white;
  font-family: "Montserrat";
  overflow: hidden;
}
.planssi2 {
  display: flex;
  flex-wrap: wrap;
  background: var(--deep-blue-color);
  padding: 1em;
  margin: 1em .25em 1em .25em;
  border-radius: 0.2vw;
  font-weight: 700;
  color: white;
  font-family: "Montserrat";
  overflow: hidden;
  height: max-content;
  width: max-content;
}
.kentat {
  padding: 1em 1em 1em 1em;
}
.kentta_1 {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
}
.kentta_2 {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
}
.kentta_3 {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
}
.break {
  flex-basis: 100%;
  width: 0;
}
.kentta_1a {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
  justify-content: end;
  margin-left: auto;
}
.kentta_2b {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
}
.kentta_3c {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
  flex: 2;
}
.kentta_1d {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
  justify-content: end;
  z-index: 1;
  position: relative;
}
.kentta_2e {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
  z-index: 0;
  position: relative;
}
.kentta_3f {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
  flex: 1;
}
.kentta_1g {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
}
.kentta_2h {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
  margin-left: auto;
}
.kentta_3i {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
  flex: 1;
}
.flex-container1 {
    display: flex;
    flex-direction: row;
    width: max-content;
}
.flex-container2 {
    display: flex;
    flex-direction: column;
    width: max-content;
}
.kentta_1j {
  background: var(--yle-blue-color);
  padding-right: 1em;
  text-align: left;
  align-self: center;
  height: calc(100% - 2em); /* korkeus: 100% - parent divin padding x 2 */
  max-height: 100%;
  line-height: 4.5em; /* säädä teksti korkeussuunnassa line-height:llä */
}
.kentta_2k {
  background: var(--violet-color);
  padding-right: 1em;
  text-align: left;
}
.kentta_3l {
  background: var(--breaking-color);
  padding-right: 1em;
  text-align: left;
  max-height: 100%;
}
</style>
##Kolme tekstikenttää päällekkäin
<div id="main" class="main">
  <div class="planssi1">
    <div class="kentat kentta_1"><div id="f0">Kenttä 1</div></div>
    <div class="kentat kentta_2"><div id="f1">Kenttä 2</div></div>
    <div class="kentat kentta_3"><div id="f2">Kenttä 3</div></div>
  </div>
</div>
</html>
