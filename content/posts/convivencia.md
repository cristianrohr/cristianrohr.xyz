---
title: "History of 'Convivencia' a generative art project - and its personal background"
date: 2022-08-07T18:24:09-03:00
draft: true
tags: ["generativeart", "creativecoding", "convivencia", "fxhash", "mint"]
type: "post"
image: "/images/projects/convivencia/convivencia_1000x1000.png"
showTableOfContents: false
---

# About the project

**Convivencia** is a generative art project in the Tezos network. It consists of 350 pieces and will be available on the [fxhash](https://www.fxhash.xyz/) platform.

'Convivencia' is a Spanish word that means _coexistence_. The title has a background, which I will explain in the end of the post, first I want to tell the characteristics and challenges encountered during the development.

![Convivencia](/images/projects/convivencia/convivencia_800x800.png)
*Test mint for Convivencia*

This project has a number of substantial differences with respect to my previous projects, namely:

## Project duration

It's been almost 3 months since I started, in which I practically don't remember a day in which I haven't spent at least 10 minutes to test ideas, modify parameters, adjust palettes. Even the days when I was working on other projects like [Varillas](https://www.fxhash.xyz/generative/slug/varillas), I always found the time to dedicate to this project. The base algorithm was ready quickly, just a few days of programming. After the algo was more or less working I had a couple of weeks of debugging, then about a month of coarse parameter tuning, and the rest of the time fine tuning, palettes selection, combinations analysis.

The parameter tuning was the most crucial and challenging point of the whole project. Both coarse and fine tuning. I had the need to balance the system so that it would generate outputs that were
- visually appealing
- diverse
- minimalistic
- but also I wanted some outputs to be complex and intricate


The coarse parameter tuning was to define a set of _optimal initial parameters_, it is complicated to define optimal, because art is in the eyes of the beholder. In this case for at least for me, optimal parameters were the parameters that would give me a balanced output from an artistic point of view (neither so minimalist nor so complex, at least in a significant % of attempts), then I needed to give degrees of freedom to the parameters, the question was how to achieve it to get the four desired characteristics, with the complication that by the nature of the algorithm itself very similar parameters can deliver very dissimilar outputs, and that reason made it much more complicated to find a fair balance (that's why I mentioned a significant % of attempts).

Also the extension in time was due to the other important challenge I wanted to take on, and that is to generate a print ready project.


## Printing ready

From the beginning I was determined that this project would be ready to be printed and framed. With this in mind I made different decisions. The first was to order prints at different stages of the project to see how they were coming along and how they would look IRL.

![Comparison_prints](/images/projects/convivencia/IMG_20220805_094835.jpg)
*How it started (up) versus how it ended (down). The evolution of the detail level put into perspective the fine tunning in the project.*

As the vast majority of generative art projects in fxhash the system has elements of rarity that are attributed to the minted image, however in this project - being print ready - I leave the freedom to the user to modify them so they can generate the image they are interested in printing. This implies a certain degree of interactivity, so that the owner of the image can make small adjustments until he finds the coexistence - convivencia - of parameters that he finds more attractive or balanced.

The attributes that can be modified in the 'live view' are
- Texture: there are three types of background texture that can be activated or deactivated, one with non-uniformly distributed dots and the other in the form of random lines distributed more evenly, and a texture based on geometric shapes (Grained texture, Lines texture, Organized texture)
- Internal decoration of shapes (Shape decoration)
- Shadow (Shape shadow)
- Border of the shapes (Shape border)
- Line type (solid or dotted)
- Show or hide the lines

![Textures](/images/projects/convivencia/Convivencia.png)
*Textures available on Convivencia*

![Attributes](/images/projects/convivencia/Convivencia2.png)
*Some attributes that you can change on live view*

You can't adjust the following parameters
- Focus (how much of the canvas frame the image can extend)
- Frame width
- Line stroke
- Palette

So in total the project have 11 attributes (Focus, Frame width, Grained texture, Line stroke, Line type, Lines texture, Organized texture, Palette, Shape border, Shape decoration, Shape shadow).


### History behind the name

A few months ago I was diagnosed with a hereditary disease called hemochromatosis. This disease consists in the accumulation and therefore overload of iron in the body which is harmful. There is no treatment or medication to cure the disease. The treatment is palliative and consists mostly of lifestyle changes or adjustments (frequent phlebotomies, diet low in iron and vitamin C among other things, eliminating alcohol, etc).

My thoughts and actions in the last time were marked by this coexistence with illness and the adjustments and tests that I have to do to control the iron levels in my body. Making an analogy in this project, the user can choose which adjustments to make to the image to obtain the version that most pleases him/her to download.

![more_prints](/images/projects/convivencia/IMG_20220805_095603.jpg)
*I just love generative art prints IRL*

After mint I probably write down a blog post talking about technical details.
