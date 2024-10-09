---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: 09_sfmoma_Kentridge_StereoscopeDrawing_Web.jpg
# some information about your slides (markdown enabled)
title: "Animated Images: A Short History"
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

## A Short History
# Animated Images

Kaveh Rafie, 10/9/24 

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: two-cols
---

![](/lascaux-torch.png){class="h-110"}

::right::

![](/lascaux-image.png){class="h-80 object-contain"}
Prehistoric paintings, Lascaux caves, southwest France, c. 15,000 BCE{class="text-xs"}

<!--
Here is another comment.
-->

---
layout: two-cols
transition: slide-up
---

![](./bodley.png){class="h-110"}
A page of the Bodley Codex, c. 14th-15th. {class="text-xs"}

::right::


![](./naramsin.png){class="h-110 object-contain m-auto"}
Victory of Naram-Sin over the mountain tribe of the Lullubi and their king Satuni, 2250 BCE, limestone.{class="text-xs"}


---
layout: center
---

![](./riley-movement.png){class="h-110 object-contain"}
Bridget Riley, Movement in Squares, 1961.{class="text-xs"}

---
layout: two-cols
---
## The 18th and 19th century technologies

![](./choreutoscope.png){class="h-80 object-contain"}
Choreutoscope, replica of an original from 1866.{class="text-xs"}

::right::
![](./fantasmagorie.png){class="w-100 h-100 object-contain m-auto"}
Fantasmagorie, probably 1797, depicted in an engraving in Étienne Gaspard Robertson’s Mémoires Récréatifs Scientifiques et Anecdotiques, 1831.{class="text-xs m-auto"}

<!-- 
the choreutoscope, held six images that, when 
projected in rapid succession, simulated simple animated 
movement 

Ghost stories, known as 
phantasmagoria, became the basis 
for a popular form of magic￾lantern performance at the end 
of the eighteenth century (1.6, 
see p. 16). In such shows, portable 
lanterns were hidden behind a translucent screen and used to project frightening 
images onto its surface. The Belgian scientist and artist 
Étienne Gaspard Robertson (1763–1837) is probably 
the best-known presenter of phantasmagoria

-->


---
layout: center
layoutClass: gap-16
---
## Zoetrope
![](./zoetrope.png){class="h-110"}

<!--
A zoetrope, meaning “wheel of life,” is another 
motion device that uses a series of images, in this 
case printed on a strip of paper that is placed inside a 
spinning drum (1.9). When the viewer looks through slits 
in the edge of the drum, he or she sees a continuous loop 
of motion. 
-->


---
layout: iframe
url: https://www.youtube.com/embed/40__creuq7c?si=P-v2TaNTGutLROzk
---


---
layout: two-cols
---
## The Impact of Photography on Studies of Locomotion

<div v-click.hide>

![](./jules-marey.png){class="h-60 object-contain" }
Étienne-Jules Marey, chronophotograph depicting a pole vault, 1887.{class="text-xs"}

</div>

<div v-after>

![](./photographic-gun.png){class="h-60 absolute top-30 object-contain"}
Étienne-Jules Marey’s “photographic gun,” 1882.{class="text-xs"}
</div>

::right::
![](./muybridge.png){class="h-90 object-contain"}
Eadweard Muybridge, motion study of a horse running, 1878.{class="text-xs"}


<!--
 In the 1830s, 
 the invention of the 
daguerreotype, a system that employed photographic 
plates to capture images. 

 Single-plate chronophotography captured 
the figure’s entire sequence of movements on a single 
photographic plate, creating superimposed images that 
revealed patterns of movement not so easily discerned 
when using separate frames

The English photographer Eadweard Muybridge 
(1830–1904), who carried out much of his work in the 
US, is well known for recording a running racehorse in 
Sacramento, California.

Meanwhile, in France, the scientist and physiologist 
Étienne-Jules Marey (1830–1904) had begun his study 
of human and animal locomotion in 1867

 In 1882, he constructed a 
“photographic gun,” known as the fusil photographique, 
that allowed him to take a series of images of a bird in 
flight by pulling a trigger to record photographs at a rate 
faster than 1/500th of a second 

-->

---
layout: two-cols
---

![](./duchamp-desc-painting.png){class="h-110 object-contain"}
[Marcel Duchamp, "Nu descendant un escalier n° 2," 1912.]{class="text-xs"}

::right::

<div v-click>

![](./duchamp-desc-photo.png){class="h-110 object-contain"}
Eliot Elisofon, Marcel Duchamp descends staircase, reproduced in Life magazine, April 28, 1952.{class="text-xs"}
</div>


---
layout: iframe-right
url: https://www.youtube.com/embed/Y6b0wpBTR1s?si=T5AVUF9sVhXftbt9
---

![](./the-black-maria.png){class="h-110 object-contain"}
Thomas Edison’s studio, the “Black Maria,” in use 1892–1901.{class="text-xs"}

<!--

Edison’s film-related machines 
included an individual viewer for motion pictures 
called the Kinetoscope and a camera called the 
Kinetograph. Edison’s first screening, held in 1896 
in New York City, featured individuals he had filmed 
in his specially constructed New Jersey studio, the 
“Black Maria” (2.6). In 1901, he built another studio, 
this one on a rooftop in New York City, which had 
glass walls to enable him to use natural lighting.

-->

---
layout: iframe
url: https://www.youtube.com/embed/aEAObel8yIE?si=dQex2BHcvKUYLDr3
---

Émile Cohl, Fantasmagorie, 1908.

<!--
The French artist Émile Cohl (born Émile Eugène Jean 
Louis Courtet, 1857–1938) was in his fifties when he 
came to cinema and began animating, after moving 
in Parisian modern-art circles for a number of years. 

Cohl completed his first film, Fantasmagorie, 
in 1908, for the Gaumont studio in France (3.1). 
Although this film seems to be drawn as chalk lines on a 
blackboard, in the style of Blackton’s lightning sketches, 
in this case Cohl actually drew black lines on white paper; 
after filming, the white-on-black effect was achieved by 
reversing the print (turning black into white and white 
into black)
-->

---
layout: iframe-right
url: https://www.youtube.com/embed/AfsU50X4Fjk?si=WpjR9hcjg86UNjm7
---

![](./rotoscope.png){class="h-110 object-contain"}
Diagrams from Fleischer’s patent for the rotoscope process, filed in 1915 and granted in 1917.{class="text-xs"}

<!--
The Clown's Pup | 1919 | Out of the Inkwell | 16mm | Koko the Clown | Max Fleischer Studios Cartoon
- cel-animation developed in the mid-1910 by Bray's comp.

Max (1883–1972) and Dave Fleischer (1894–1979) were 
among the first to experiment with recorded sound in 
animated films during the 1920s. 

Max Fleischer was hired in 1916 and brought 
with him the patent for the rotoscope process (filed in 
1915 and granted in 1917), in which footage of a live 
performer is projected frame by frame onto paper and 
then traced to form the basis for drawings of animated 
characters (3.11a, 3.11b). Fleischer used the process in 
his “Out of the Inkwell” entertainment films featuring 
Koko the Clown.

-->



---
layout: iframe
url: https://www.youtube.com/embed/mmUygx-f4VA?si=DXu8GCgJlZ51wR_1
---

<!--
Walt Disney, Trolley Troubles, 1927
Trolley Troubles is a 1927 animated short subject film, produced by Charles Mintz and George Winkler and directed by Walt Disney
-->


---
layout: iframe-right
url: https://www.youtube.com/embed/92KFRJLhi_E?si=BgTN4rtuoyUxQrOE
---
## Silhouette Animation
![](./mutiplane-rig.png){class="h-90 object-contain"}

Lotte Reiniger and Carl Koch at work on a multiplane rig, creating The Adventures of Prince Achmed, c. 1925.{class="text-xs"}

<!--
 Charlotte "Lotte" Reiniger (2 June 1899 – 19 June 1981) was a German film director and the foremost pioneer of silhouette animation.
-->

---
layout: iframe
url: https://www.youtube.com/embed/239pHUy0FGc?si=FPpQykyasBu9Gi8l
---

## Abstract Animation
Hans Richter, Rhythm 21, 1921


---
layout: iframe
url: https://www.youtube.com/embed/bkJwE2Q9Cac?si=OmZ6JxPCsubdYu4q
---

<!--
 Walther Ruttmann, Lightplay: Opus I, 1921
 Walter Ruttmann (28 December 1887 – 15 July 1941) was a German cinematographer and film director, an important German abstract experimental film maker, along with Hans Richter, Viking Eggeling and Oskar Fischinger. 
-->


---
layout: iframe
url: https://www.youtube.com/embed/77X6G0wcpZU?si=0jCt5B0eUZSdFni4
---

<!--
Composition In Blue by Oskar Fischinger (excerpt)
-->

---
layout: iframe
url: https://www.youtube.com/embed/zXqIKlCzqL0?si=Rh2Js9JT8kCk2pAx
---

<!--
Oskar Fischinger, a pioneer in abstract film, created a series of experiments using wax in the early 1920s. These Wax Experiments I (1921-1926) showcased his innovative techniques and artistic vision.

Process: Fischinger tinted layers of hot wax, allowing them to cool and form a lump resembling a marble cake. He then cut off slices from the lump, photographing each step. This process created intricate, abstract patterns and shapes.

He made a series of Wax Experiments in the 1920s, but only a few of these have been restored so far (we're looking for sponsors for further restoration of these experiments which are sadly deteriorating).  
-->


---
layout: iframe
url: https://www.youtube.com/embed/__5B3PGoBoI?si=8yUR99fzleqKf_VL
---

<!--
The Cameraman's Revenge (1912) 
The Cameraman's Revenge (Russian: Месть кинематографического оператора, romanized: Mest' kinematograficheskogo operatora) is a 1912 Russian short film written and directed by Ladislas Starevich.[1][2][3] It, along with other works by Starevich, stands out in the history of stop-motion animation for its use of actual dried insect specimens (beetles, grasshoppers, dragonflies, etc.) as articulated stop-motion puppets portraying all of the characters.

Bored with married life, Mr. Beetle goes to a nightclub and fights off a grasshopper for the attention of a dragonfly dancer. Little he knows, the grasshopper is a cameraman who follows the couple to the home of the dragonfly and films their amorous encounter. When Mr. Beetle returns home, he finds Mrs. Beetle in the arms of a young artist, another beetle. After throwing the intruder out, Mr. Beetle magnanimously forgives his wife. Together they go to the movies, and, to their surprise, the film being shown is of Mr. Beetle’s infidelity. Mrs. Beetle is not happy. The date ends when the couple gets thrown in a prison cell.
-->

---
layout: two-cols
---

![](./snow-white.png){class="h-110 object-contain"}
Walt Disney Pictures, Snow White and the Seven Dwarfs, 1937.{class="text-xs"}

::right::

![](./disney-cels.png){class="h-100 object-contain mx-auto"}
[A Disney animator working on cels of Mickey Mouse, 1938.]{class="text-xs text-center px-10"}


---
layout: two-cols
---

![](./popeye.png){class="h-110 object-contain"}
Dave Fleischer, Popeye the Sailor Meets Sinbad the Sailor, 1936.{class="text-xs"}

::right::
![](./stereoptical-process.png){class="h-100 object-contain mx-auto"}
Fleischer’s patent for the Stereoptical process, 1936.{class="text-xs p-10 block text-center"}

---
layout: center
---

![](./mclaren-v.png){class="h-110 object-contain"}
Norman McLaren, V for Victory, 1941.{class="text-xs"}

<!--
 Norman McLaren, V for Victory, 1941
William Norman McLaren, CC CQ LL. D. (11 April 1914 – 27 January 1987) was a Scottish Canadian animator, director and producer known for his work for the National Film Board of Canada (NFB).[1] He was a pioneer in a number of areas of animation and filmmaking, including hand-drawn animation, drawn-on-film animation, visual music, abstract film, pixilation and graphical sound.
-->

---
layout: iframe
url: https://www.youtube.com/embed/SZFu0Kno7aw?si=HtHw6V4EQPlHZS29
---

<!--
Dots - Norman McLaren (1940)
-->

---
layout: center
---

![](./jodoin.png){class="h-110 object-contain"}
René Jodoin, Dance Squared, 1961.{class="text-xs"}

<!--
René Jodoin (30 December 1920 – 22 January 2015) was an animation director and producer who founded the French-language animation studio of the National Film Board of Canada. Born in Hull, Quebec on December 30, 1920, Jodoin died in Montreal on January 22, 2015 at the age of 94.
-->

---
layout: iframe
url: https://www.youtube.com/embed/FuOcZIEszIk?si=wRsNBni8vYZVMWiC
---

<!--

 Dušan Vukotic´, Ersatz, 1961
 a Yugoslav and Croatian-Montenegrin cartoonist,
-->

---
layout: iframe
url: https://www.youtube.com/embed/wFAoLHXou4s?si=Tlom6Z_sqie0q4iW
---

<!--
The Hand (1966) Jiri Trnka
The Hand (Czech: Ruka) is a 1965 Czechoslovak stop motion puppet animation film directed by Jiří Trnka. It was to be Trnka's final film.
The film was first released in 1965. When Trnka died in 1969, the film was banned due to its story that reflects a restrictive environment in which many artists had to work.

-->


---
layout: center
---

## Contemporary art and animation

![](./kentridge-exh.png){class="h-110 object-contain"}
William Kentridge, Why Should I Hesitate, 2020-1.{class="text-xs"}

---
layout: iframe
url: https://www.youtube.com/embed/5_UphwAfjhk?si=AiSM73SCq7lfYAqL
---

<!--

William Kentridge: transformation with animation
-->