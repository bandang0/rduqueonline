---
layout: page
title: Projects
showhead: true
---

### AstroReduce

[AstroReduce](https://github.com/bandang0/astro_reduce) is a simple astronomical image reduction program commissioned by the Observatoire de Paris for fast and straightforward reduction of series of images during pedagogical observing sessions at the Observatoire de Haute-Provence. In addition to reducing stacks of astronomical images, AstroReduce interfaces with the [Astromatic](https://github.com/astromatic) software suite for rapid source extraction, photometry and astrometry. It is under continuous development, do contact me to contribute!

![alt text](../img/astro_reduce.png "Sample AstroReduce CLI output")


### The Automatic Astrophysical Model Generator (AAMG)

The [AAMG](https://github.com/bandang0/aamg) stemmed from the idea that our current understanding of some astrophysical phenomena (especially in high-energy astrophysics) could have come about earlier if someone had randomly stumbled upon a statement of the (now-acknowledged) correct model for the phenomenon, instead of having to wait for the model to crop up from a rational and conscious string of thought or analysis.

The AAMG is a program which parses a formal grammar and lists of possible words for every grammatical function (referred to as *assets*) and generates grammatically correct random sentences. If the assets are chosen from the vocabulary of astrophysics, the random sentences are in fact astrophysical models, which just might be correct or can simply nourish the reflection on a misunderstood phenomenon. The method is an instance of randomness-driven creativity, analogous to [aleatorism](https://en.wikipedia.org/wiki/Aleatoric_music) in music.

Another interesting usage of the AAMG is to try point out precisely why the scenarios it proposes for a given phenomenon are not valid. Through order-of-magnitude calculations--which are always a good exercise--, one can invalidate scenarios for their energy budgets, efficiencies, length or time scales, rates, etc.

The parser-generator is continuously under improvement, and the long-run perspective is for the community to contribute grammars and assets to explore even further the extent of possible astrophysical models.
