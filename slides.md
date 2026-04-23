---
# try also 'default' to start simple
theme: seriph
fonts:
  sans: 'Luxurious Roman'
  serif: 'PT Serif'
  mono: 'Fira Code'
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.de
# some information about your slides (markdown enabled)
title: Servus!
info: |
  ## Slidev Starter Template

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: view-transition
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
# duration of the presentation
duration: 35min
dragPos:
  square: 112,216,800,40
---

# Titel

<img v-drag="[0,0,1080,750]" src="https://www.greekmyths-greekmythology.com/wp-content/uploads/2024/12/pygmalion-galatea-statue-regnault-800x602.webp">

<div v-drag="[200,700,500,10]" class="text-[#6F9DBE]" text-center text-3xl  style="view-transition-name: pic;">
    Pygmalion 
    und
    Galatea
</div>

---
transition: slide-left
---

# Titel

<img v-drag="[0,0,1080,750]" src="https://www.greekmyths-greekmythology.com/wp-content/uploads/2024/12/pygmalion-galatea-statue-regnault-800x602.webp">

<div 
  v-drag="[0, 0, 980, 555]" 
  style="
    background-color: rgba(0, 0, 85, 0.3); 
    position: absolute;
  ">
</div>

<div v-drag="[200,75,500,10]" class="text-[#6F9DBE]" text-center text-9xl style="view-transition-name: pic;">
    Pygmalion 
    und
    Galatea
</div>

---
transition: view-transition
---

<img v-drag="[500, 2, 403, 547]" src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Pygmalion_%28V%C3%A9rard%29.jpg" style="view-transition-name: pic; z-index: 1;" />

<img v-drag="[500, 800, 403, 547]" src="https://www.griechenland-auskunft.de/bilder/pygmalion-und-galatea.jpg" style="view-transition-name: pic2; z-index: 2;" />

<div v-drag="[50, 150, 20, 10]" class="text-[#6F9DBE] text-center text-8xl">
    Der Mythos
</div>

---
transition: slide-up
---

<img v-drag="[500, 2, 403, 547]" src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Pygmalion_%28V%C3%A9rard%29.jpg" style="view-transition-name: pic; z-index: 1;" />

<img v-drag="[500, 2, 403, 547]" src="https://www.griechenland-auskunft.de/bilder/pygmalion-und-galatea.jpg" style="view-transition-name: pic2; z-index: 2;" />

<div v-drag="[50, 150, 20, 10]" class="text-[#6F9DBE] text-center text-8xl">
    Der Mythos
</div>

<style>
h1 {
  background-color: #786666;
  background-image: linear-gradient(45deg, #786666 10%, #786666 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-left
image: https://ids.si.edu/ids/deliveryService?id=SAAM-1966.47.85_1&max=2600
transition: slide-right
---

<div v-drag="[160,50,1000,60]" class="text-[#6F9DBE] text-center text-5xl">
    Geschichte
</div>
    
<div v-drag="[520,120,1000,60]" class="text-[#6F9DBE] text-left text-3xl" >
    -älteste Darstellung:<br>‎ von Philostephanos von Kyrene <br><br>-ausführlichste Darstellung:<br>‎ in Metamorphosen von Ovid
</div>

<div v-drag="[0,520,500,60]" class="text-[#6F9DBE] text-left text-xs" >
    Paul Manship, Pygmalion and Galatea, 1963, gilded bronze on marble base, 11 in. (27.9 cm), Smithsonian American Art Museum, Bequest of Paul Manship, 1966.47.85
</div>

---
transition: slide-down
---

<div v-drag="[-230,50,1000,60]" class="text-[#6F9DBE] text-center text-5xl">
    Der Pygmalion Effekt
</div>
    
<div v-drag="[50,120,1000,60]" class="text-[#6F9DBE] text-left text-3xl" >
    -Erwartungen <br>‎ beeinflussen Leistung<br><br>-auch selbsterfüllenden <br>‎ Prophezeiung genannt<br><br>-bewiesen druch<br>‎ ‎Rosenthal-Experiment  
</div>

<img v-drag="[530,0,1000,550]" style="width: 1200px !important; max-width: none !important; min-width: 1000px;" src="https://substackcdn.com/image/fetch/$s_!QJuw!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F91c0d1f7-5a63-403e-9c2e-f6ea55fe9259_3239x1523.png">

---
transition: slide-left
layout: iframe
url: https://www.krigolsonteaching.com/uploads/4/3/8/4/43848243/teacher_impact_on_self_confidence.pdf
---

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>


<div v-drag="[-400,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage1">
    1.Wie hieß der Bilderhauer?<br><br>‎A) Pyrotechniker<br><br>‎B) Pylonion<br><br>‎C) Pygmalion
</div>




<div 
  v-drag="[600, 100, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung1;"
></div>

<div 
  v-drag="[600, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>


<div v-drag="[100,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage1">
    1.Wie hieß der Bilderhauer?<br><br>‎A) Pyrotechniker<br><br>‎B) Pylonion<br><br>‎C) Pygmalion
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div 
  v-drag="[600, 100, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung1;"
></div>

<div 
  v-drag="[600, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>


<div v-drag="[100,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage1">
    1.Wie hieß der Bilderhauer?<br><br>‎A) Pyrotechniker<br><br>‎B) Pylonion<br><br>‎C) Pygmalion
</div>

<div v-drag="[-400,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage2">
    2.Wie hieß die Statue in Ovids Darstellung?<br><br>‎A) Galatea<br><br>‎B) Hans Wurst<br><br>‎C) Sie hatte kein Namen
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div v-drag="[650,300,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Sie hatte<br>kein Namen
</div>

<div v-drag="[650,450,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div 
  v-drag="[1200, 100, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung1;"
></div>

<div 
  v-drag="[600, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>

<div v-drag="[-400,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage1">
    1.Wie hieß der Bilderhauer?<br><br>‎A) Pyrotechniker<br><br>‎B) Pylonion<br><br>‎C) Pygmalion
</div>

<div v-drag="[100,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage2">
    2.Wie hieß die Statue in Ovids Darstellung?<br><br>‎A) Galatea<br><br>‎B) Hans Wurst<br><br>‎C) Sie hatte kein Namen
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div v-drag="[650,270,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Sie hatte kein<br>Namen
</div>

<div v-drag="[650,450,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div 
  v-drag="[600, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>

<div v-drag="[100,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage2">
    2.Wie hieß die Statue in Ovids Darstellung?<br><br>‎A) Galatea<br><br>‎B) Hans Wurst<br><br>‎C) Sie hatte kein Namen
</div>

<div v-drag="[-600,130,500,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage3">
    3.Wie hieß das Experiment, das den Pygamlion-Effekt bewiesen hat?<br><br>‎A) Oberwiesental-Experiment<br><br>‎B) Keine Ahnung ich hab nicht aufgepasst<br><br>‎C) Rosenthal-Experiment
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div v-drag="[650,270,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Sie hatte kein<br>Namen
</div>

<div v-drag="[650,450,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div 
  v-drag="[1200, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: view-transition
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>

<div v-drag="[-400,130,400,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage2">
    2.Wie hieß die Statue in Ovids Darstellung?<br><br>‎A) Galatea<br><br>‎B) Hans Wurst<br><br>‎C) Sie hatte kein Namen
</div>

<div v-drag="[100,130,500,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage3">
    3.Wie hieß das Experiment, das den Pygamlion-Effekt bewiesen hat?<br><br>‎A) Oberwiesental-Experiment<br><br>‎B) Keine Ahnung ich hab nicht aufgepasst<br><br>‎C) Rosenthal-Experiment
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div v-drag="[650,270,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Sie hatte kein<br>Namen
</div>

<div v-drag="[650,420,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Rosenthal-<br>Experiment
</div>

<div 
  v-drag="[1200, 250, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung2;"
></div>

<div 
  v-drag="[600, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: slide-up
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Ein Quiz!!!
</div>

<div v-drag="[100,130,500,50]" class="text-left text-3xl text-[#6F9DBE]" style="view-transition-name: frage3">
    3.Wie hieß das Experiment, das den Pygamlion-Effekt bewiesen hat?<br><br>‎A) Oberwiesental-Experiment<br><br>‎B) Keine Ahnung ich hab nicht aufgepasst<br><br>‎C) Rosenthal-Experiment
</div>

<div v-drag="[650,150,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Pygmalion
</div>

<div v-drag="[650,270,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Sie hatte kein<br>Namen
</div>

<div v-drag="[650,420,400,50]" class="text-left text-3xl text-[#6F9DBE]">
    C) Rosenthal-<br>Experiment
</div>

<div 
  v-drag="[1200, 400, 300, 130]" 
  class="bg-[#4A4A4A] border-2 border-[#949494] rounded-xl shadow-lg" style="view-transition-name: überdeckung3;"
></div>

---
transition: slide-right
---

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
    Quellen
</div>

<div v-drag="[100,130,500,50]" class="text-left text-xs text-[#6F9DBE]" style="view-transition-name: frage3">
    https://histoires-du-monde.com/de/griechische-mythologie/pygmalion-und-galatea-ein-mythos-der-personlichen-transformation/
    http://special.lib.gla.ac.uk/exhibns/month/feb2000.html, Gemeinfrei, https://commons.wikimedia.org/w/index.php?curid=4534624
    https://www.griechenland-auskunft.de/pygmalion.php
    Yannis Samatas. "The Myth of Pygmalion and Galatea." greekmyths-greekmythology.com, 3 Dec. 2010. Updated 28 May. 2025, https://www.greekmyths-greekmythology.com/myth-of-pygmalion-and-galatea/.
    https://2mins.substack.com/?utm_campaign=pub&utm_medium=web
    https://de.wikipedia.org/wiki/Pygmalion
    https://www.greekmyths-greekmythology.com/wp-content/uploads/2024/12/pygmalion-galatea-statue-regnault-800x602.webp
    https://upload.wikimedia.org/wikipedia/commons/1/1b/Pygmalion_%28V%C3%A9rard%29.jpg (Von Antoine Vérard; Du Pré)
    https://www.griechenland-auskunft.de/bilder/pygmalion-und-galatea.jpg (Pygmalion und die zu Leben Galatea - Bild von Jean-Léon Gérôme)
    https://substackcdn.com/image/fetch/$s_!QJuw!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F91c0d1f7-5a63-403e-9c2e-f6ea55fe9259_3239x1523.png
    https://ids.si.edu/ids/deliveryService?id=SAAM-1966.47.85_1&max=2600
</div>

---
transition: slide-right
---


<img 
  v-drag="[100,75,800,450]" 
  src="https://i.pinimg.com/1200x/d1/17/89/d117898540d3b5e8f6921295a8a3617e.jpg" 
/>

<div v-drag="[300,0,400,50]" class="text-left text-7xl text-[#6F9DBE]">
  Das ENDE
</div>

<div v-drag="[730,450,400,50]" class="text-left text-xs text-[#6F9DBE]">
  Bitte eine 1
</div>
