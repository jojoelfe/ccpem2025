---
# You can also start simply with 'default'
theme: ./theme
# some information about your slides (markdown enabled)
title: Johannes Elferich - Happy hour 03/2025

# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
canvasWidth: 1080
layout: intro-image
image: '/cover.png'
colorSchema: dark

---

<div class="absolute top-10">
  <span class="font-700 drop-shadow-[0_1.2px_1.2px_rgba(0,0,0,0.8)]">
    Johannes Elferich 03/12/2025
  </span>
</div>

<div class="absolute bottom-10">
  <h1 class="drop-shadow-[0_1.2px_1.2px_rgba(0,0,0,0.8)]">In-Situ High-Resolution Cryo-EM Reconstructions from CEMOVIS</h1>
  </div>

---
class: bg-black
layout: intro-image
---

# Synapses

<SlidevVideo controls class=" h-110 mx-auto">
<source src="/brain.mp4"  />
</SlidevVideo>

<p class="cite text-right text-sm absolute right-4 top-140 text-white">Allen Institute / Qurometrix</p>

---
class: bg-black pa-0

layout: intro-image

---

<SlidevVideo controls class=" h-110 mx-auto">
<source src="/milling.webm"  />
</SlidevVideo>
---
class: bg-black pa-0

layout: intro-image

---

<SlidevVideo controls class=" h-full mx-auto">
<source src="/media2.mp4"  />
</SlidevVideo>

---
class: bg-black pa-0

layout: intro-image
---
<Youtube id="1E1g4ivWtec" class=" h-full w-full" />

---

# What does the grid look like

<img src="/fig1.png" class="h-120 mx-auto"/>

---

# Micrographs can be nice quality

<img src="/fig1b.png" class="h-60 mx-auto mt-20 rounded"/>

--- 

# But not always

<img src="/badcistem.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Let's test quality using 2DTM!

<img src="/fig2a.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Let's test quality using 2DTM!

<img src="/fig2b.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Let's test quality using 2DTM!

<img src="/fig2c.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Let's test quality using 2DTM!

<img src="/fig2d.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Can we make a good reconstruction?

<img src="/fig2a.png" class="h-63 mx-auto mt-2 rounded"/>
<img src="/fig3a.png" class="h-60 mx-auto mt-2 rounded"/>

---

# Whats the resolution?

<img src="/fig3b.png" class="h-120 mx-auto mt-2 rounded"/>

---

# What does the map looks like - L34A

<img src="/fig3c.png" class="h-120 mx-auto mt-2 rounded"/>

---
class: bg-black pa-0

layout: intro-image

---

<SlidevVideo controls class=" h-full mx-auto">
<source src="/output.mp4"  />
</SlidevVideo>

--- 

# Where does the damage come from?

<img src="/fig4a.png" class="h-60 mx-auto mt-20 rounded"/>

--- 

# Where does the damage come from?

<img src="/fig4b1.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Where does the damage come from?

<img src="/fig4b2.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Where does the damage come from?

<img src="/fig4b3.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Ripley's L function

<div style="display: flex; justify-content: center; align-items: center;">
  <div style="text-align: center; margin-right: 20px;">
  <p>CEMOVIS</p>
    <img src="/ripley_cemovis.png" class="h-110 mt-2 rounded"/>
    
  </div>
  <div style="text-align: center;">
  <p>FIB</p>
    <img src="/ripley_fib.png" class="h-110 mt-2 rounded"/>
    
  </div>
</div>


---

# Where does the damage come from?

<img src="/fig4b4.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Where does the damage come from?

<img src="/fig4c.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Where does the damage come from?

<img src="/fig4d.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Summary

- Does CEMOVIS produce higher-quality cell slices than FIB-milling: NO
- Is the quality high enough to get residue-level resolution: YES
- We should pursue this, because the advantages in terms of data quantity and continuity are exciting
  - Let's use 2DTM to optimize parameters of sectioning
  - Let's use Deco-LACE to image adjacent sections and stitch them together