# Parametric versus Raster brush
Author: Americo Americo</br>
Date: 2018 June

![](parametric-brushes.assets/parametric-brushes-noise-in-my-head-2013.jpeg)
<div style="font-size:small">_Noise in my head, by Jag, 2013._</div>

## Which is better as classical brush, the parametric or a raster brush?

On GIMP the brush set have a small amount of parametric brushes… why reason? Sincerely I do not know, perhaps, many illustrators, concept artists, photographers have been accustomed to see/utilize only raster brushes.

My idea is very simple, up to what point the parametric brush, as a classical brush, could be used on digital painting?

I thought a simple test … I did a parametric calligraphic brush, very small with a radius equal to 12 px. After I have made a stamp of my parametric brush and build a static raster brush (.gbr).

From my tests among both brushes, it results that the parametric is better than its equivalent .gbr, if are thinking in classic dabs, round, square, diamond and variations of shape forms based in spikes.

<div style="font-size:small">_Figure 1 - Simple strokes comparison between parametric and static raster brush with same seed._</div>

The default shapes are round, square and diamond. Is also possible create a great variation of the shapes, using the different parameters to control the shape and its aspect (radius, spikes, hardness, aspect ratio, angle and spacing).

The stroke of parametric brush is more sharpest and hard when we use hardness equal 1 when we compare with the raster brushes, is much easy to increase/decrease the softness via own editor or via Tool Options … instead the .gbr when we increase/decrease the hardness the stain is deformed by the blur algorithm how is possible in this gitlab issue: https://gitlab.gnome.org/GNOME/gimp/issues/1081

## How to combine parametric brushes and paint dynamics
I think is not possible have an unequivocal rule to combine brushes with paint dynamics, instead is possible to say that, in general: each paint dynamics represents an effect or a different technique.

<img src="parametric-brushes.assets/parametric-brushes-personaggio-bizarro_noises-brushes-with-my-generic-pencil-dyna.jpg" style="float: left"></img>
<div style="font-size:small">_Figure 2 - A fast sample made with many paint dynamics with the same parametric brush._</dib>

### Dry Media Experiments
I thought to begin with classic main dry media as pencil, crayon, charcoal and pastel.

I think that an unique dynamic is capable emulate practically all these dry medias. Is possible to identify many brushes, raster and/or parametric, that can be utilized with this paint dynamic … more opaque and darken is possible emulate charcoal and oil crayon … less opaque and lighter, the dry crayons and pencils.

Basically the paint dynamic emulates the technique and the brush emulates the stain quality and characteristics of the medium, but this is not always true, what I am saying is: that in certain cases some stain marks could be alone and without paint dynamics represents a good mark for a dry medium, but with limitations to use effectively to paint. In general, a good paint dynamics dedicated to a paint technique, e.g., dry media, it could work with many stain marks also with marks thought or pulled by another medium as watercolor, for instance.

To explore I have revised a bit the Pencil Generic Paint Dynamics
to adapt better it to other dry media and it [here](). [ToDo]

<div style="font-size:small">_Figure 3 - Samples using many parametric brushes with my paint dynamic for dry media._</div> [ToDo]

<div style="font-size:small">_Figure 4 - Sample with my Paint dynamics for generic dry media with airbrush and other paint tools. I’ve used the jitter to control the spread of the medium._</div>[ToDo]

### Samples and Tests
Samples and tests are published in 2013 on my g+ account and, all are realized with a paint dynamics shared [here](). [ToDo]

* Testing 0 to promote parametric brushes on GIMP. [See](https://plus.google.com/u/0/+AmericoGobbo/posts/PXvru8Rfumz)
* Comparison 1 of the dry media between parametric and raster brushes. [See](https://plus.google.com/+AmericoGobbo/posts/cLiZ6UZJ8w4)
* Comparison 2 between raster and parametric brushes with or not paint dynamics and different jitter values applied. [See](https://plus.google.com/+AmericoGobbo/posts/Jgv6q2o7Gee)
* Comparison 3 and conclusions about the behavior of paint dynamics for dry media  between parametric and raster brushes. [See](https://plus.google.com/+AmericoGobbo/posts/VHy2sNcteRK)

## Parametric Basic Brush Set
The idea to put in evidence these brushes is motivated by the real possibilities of the parametric brushes on GIMP to solve many issues of pictorial techniques with simple and dedicated paint dynamics.

This set contains the .vbr basic brushes, round and block (hard and soft versions). The 'BO' folder contains the .vbr basic brushes, round and block (hard and soft versions).

### Author, License and Download
The Brush Set [[download](todo)] was created by Americo Gobbo and licensed as Public Domain.
