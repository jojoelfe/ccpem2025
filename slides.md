---
# You can also start simply with 'default'
theme: ./theme
# some information about your slides (markdown enabled)
title: Johannes Elferich - CCPEM 04/2025

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
    Johannes Elferich 04/24/2025
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

<SlidevVideo autoplay loop muted class=" h-110 mx-auto">
<source src="/brain.mp4"  />
</SlidevVideo>

<p class="cite text-right text-sm absolute right-4 top-140 text-white">Allen Institute / Qurometrix</p>

---
class: bg-black
---

# Cryo-ET to study the architecture of the synapse

<img src="/papers/032024.png" v-click rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline/>
<img src="/papers/102024.png" v-click rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--60 mx-10/>
<img src="/papers/112024.png" v-click rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--120 mx-70/>
<img src="/papers/1120242.png"v-click  rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--30 mx-30/>
<img src="/papers/012025.png" v-click rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--90 mx-8/>
<img src="/papers/032025.png" v-click rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--120 mx-55/>
<img src="/papers/0320252.png"v-click  rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--220 mx-35/>
<img src="/papers/0320253.png"v-click  rounded-xl outline-5 outline-indigo-600 w-175 outline-solid inline mt--120 mx-60/>
v-click 
---
class: bg-black pa-0

layout: intro-image

---

<SlidevVideo autoplay class=" h-130 mx-auto">
<source src="/tomo_anim.mp4"  />
</SlidevVideo>

<div class="absolute right-8 text-center top-20">
  <img src="/eric.jpeg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Eric Gouaux</p>
  <img src="/aya.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Aya Matsui</p>
  <img src="/cathy.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Cathy Spangler</p>
</div>

<p class="cite text-right text-sm "> Cryo-electron tomographic investigation of native hippocampal glutamatergic synapses. Aya Matsui, Cathy J. Spangler, Johannes Elferich, Momoko Shiozaki, Nikki Jean, Xiaowei Zhao, Maozhen Qin, Haining Zhong, Zhiheng Yu, Eric Gouaux  eLife 2024.</p>

<!--
Maybe update with newer segmentation + tomo and move around from perfect sideview 
-->
---
---

# Is there another way?
<SlidevVideo autoplay loop class=" h-full mx-auto">
<source src="/cemovis_animation.mp4"  />
</SlidevVideo>
<!--
Replace with CEMOVIS animation
-->

---
transition: none
---

# What does the grid look like

<img src="/0002.png" class="h-120 mx-auto"/>
<!--
Maybe Zoom-in video
-->
<div class="absolute right-8 text-center top-20">
  <img src="/marek.webp" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Marek Kaminek</p>
  <img src="/wanda.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m\">Wanda Kukulski</p>
  <img src="/benoit.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Benoît Zuber </p>
  <img src="/niko.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Nikolaus Grigorieff</p>
</div>

---
transition: none
---

# What does the grid look like

<SlidevVideo autoplay mute class=" h-120 mx-auto">
<source src="/step1.mp4"  />
</SlidevVideo>
<!--
Maybe Zoom-in video
-->
<div class="absolute right-8 text-center top-20">
  <img src="/marek.webp" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Marek Kaminek</p>
  <img src="/wanda.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m\">Wanda Kukulski</p>
  <img src="/benoit.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Benoît Zuber </p>
  <img src="/niko.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Nikolaus Grigorieff</p>
</div>

---
transition: none
---

# What does the grid look like

<SlidevVideo autoplay mute class=" h-120 mx-auto">
<source src="/step2.mp4"  />
</SlidevVideo>
<!--
Maybe Zoom-in video
-->
<div class="absolute right-8 text-center top-20">
  <img src="/marek.webp" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Marek Kaminek</p>
  <img src="/wanda.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m\">Wanda Kukulski</p>
  <img src="/benoit.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Benoît Zuber </p>
  <img src="/niko.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Nikolaus Grigorieff</p>
</div>

---


# What does the grid look like

<SlidevVideo autoplay mute class=" h-120 mx-auto">
<source src="/step3.mp4"  />
</SlidevVideo>
<!--
Maybe Zoom-in video
-->
<div class="absolute right-8 text-center top-20">
  <img src="/marek.webp" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto" />
  <p class="!mt-1 text-m ">Marek Kaminek</p>
  <img src="/wanda.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m\">Wanda Kukulski</p>
  <img src="/benoit.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Benoît Zuber </p>
  <img src="/niko.jpg" class="rounded-full drop-shadow-lg w-16 h-16 mx-auto object-cover" />
  <p class="!mt-1 text-m ">Nikolaus Grigorieff</p>
</div>

---

# Powerspectra indicate high-quality data

<img src="/fig1b.png" class="h-60 mx-auto mt-20 rounded"/>
<!--
Show micrographs
-->
--- 

# But not always

<img src="/badcistem.png" class="h-120 mx-auto mt-2 rounded"/>
<!--
Quantify somehow
-->
---



<SlidevVideo mute autoplay loop class="absolute h-full ml--20 mt--10">
<source src="/2dtm.mp4"  />
</SlidevVideo>

<h1 z-1 absolute> 2D Template Matching (2DTM)</h1>
---

# 2DTM - Damage quantification & Baited reconstruction

<div grid grid-cols-2 mt-14 items-center gap-4>
<div>
<img src="/fib_damage.png" rounded mx-auto>
    B.A. Lucas, & N. Grigorieff, Quantification of gallium cryo-FIB milling damage in biological lamellae, Proc. Natl. Acad. Sci. U.S.A. 120 (23) e2301852120, https://doi.org/10.1073/pnas.2301852120 (2023). 
</div>
<div>
<img src="/baited.png" rounded mx-auto>
     Bronwyn A Lucas, Benjamin A Himes, Nikolaus Grigorieff 
(2023) Baited reconstruction with 2D template matching for high-resolution structure determination in vitro and in vivo without template bias
eLife 12:RP90486.
</div>
</div>

---

# Our yeast 60S template

<img src="/fig2a.png" class="h-120 mx-auto mt-2 rounded"/>
<!--
FIrst 1-2 slidex explaining 2DTM
-->

---
transition: fade
---

# Let's test quality using 2DTM!

<img src="/2dtm01.png" class="h-120 mx-auto mt-2 rounded"/>

---
transition: fade
---

# Let's test quality using 2DTM!

<img src="/2dtm02.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Let's test quality using 2DTM!

<img src="/2dtm03.png" class="h-120 mx-auto mt-2 rounded"/>

---

# CEMOVIS vs FIB - Number of detections

<img src="/fig2c.png" class="h-120 mx-auto mt-2 rounded"/>

---

# CEMOVIS vs FIB - Signal to Noise

<img src="/fig2d.png" class="h-120 mx-auto mt-2 rounded"/>

---

# Can we make a good reconstruction?

<img src="/fig2a.png" class="h-63 mx-auto mt-2 rounded"/>
<img src="/fig3a.png" class="h-60 mx-auto mt-2 rounded"/>

---

# Whats the resolution?

<img src="/fig3b.png" class="h-110 mx-auto mt-2 rounded"/>

<a href="https://github.com/teamtomo/torch-fourier-shell-correlation"><mdi-github />teamtomo/torch-fourier-shell-correlation</a>
---

# What does the map looks like - L34A

<img src="/fig3c.png" class="h-120 mx-auto mt-2 rounded"/>

---
class: bg-black pa-0

layout: intro-image

---

<SlidevVideo autoplay muted loop class=" h-full mx-auto">
<source src="/map_render.mp4"  />
</SlidevVideo>
<!--
Dark background
-->
--- 

# Where does the damage come from?

<img src="/fig4a.png" class="h-60 mx-auto mt-20 rounded"/>
<!--
Animation explaining slice angle
-->
--- 
transition: fade
---

# Where does the damage come from?

<img src="/start.png" class="h-120 mx-auto mt-2 rounded"/>

--- 
transition: fade
---

# Where does the damage come from?

<img src="/lp.png" class="h-120 mx-auto mt-2 rounded"/>

--- 
transition: fade
---

# Where does the damage come from?

<img src="/hist1.png" class="h-120 mx-auto mt-2 rounded"/>

--- 

# Where does the damage come from?

<img src="/hist2.png" class="h-120 mx-auto mt-2 rounded"/>

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

FIB
<img src="/fibdamage.png" class="h-50 mx-auto mt-2 rounded"/>
CEMOVIS
<img src="/cemovisdamage.png" class="h-50 mx-auto mt-2 rounded"/>

---

# Summary

<v-clicks>

- Does CEMOVIS produce higher-quality cell slices than FIB-milling: **NO** (Not yet?)
- Is the quality high enough for *in-situ* structural biology: **YES**
- We should pursue this, because the advantages in terms of data quantity and continuity are exciting
- Let's use 2DTM to optimize CEMOVIS parameters
- Let's combine CEMOVIS and montaged acquisition to do **Cryo-Volume EM**

</v-clicks>

<style>
  li {
font-size: 1.4em;

  }
  li > strong {
    font-size: 1.1em;
    font-weight: 1200;
  }
</style>
--- 

# Thank you!