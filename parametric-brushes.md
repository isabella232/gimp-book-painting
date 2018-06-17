# Parametric versus Raster brush
Author: Americo Gobbo<br>
Date: 2018 June

<figure><img src="parametric-brushes.assets/parametric-brushes-personaggio-bizarro.jpg" width="640">
<figcaption><br>A fast sample made in 2013 by Americo Gobbo with Dry Media paint dynamics and parametric brushes.</figcaption>
</figure>

## Which is better as classical brush, the parametric or a raster brush?
On GIMP the brush set have a small amount of parametric brushes… why reason? Sincerely I do not know, perhaps, many illustrators, concept artists, photographers have been accustomed to see/utilize only raster brushes.

My idea is very simple, up to what point the parametric brush, as a classical brush, could be used on digital painting?

I thought a simple test … I did a parametric calligraphic brush, very small with a radius equal to 12 px. After I have made a stamp of my parametric brush and build a static raster brush (.gbr).

From my tests among both brushes, it results that the parametric is better than its equivalent .gbr, if are thinking in classic dabs, round, square, diamond and variations of shape forms based in spikes.

![](parametric-brushes.assets/parametric-brushes-dialog-editor.png "Image Title")<br>*Brush set and Parametric Editor*

The default shapes are round, square and diamond. Is also possible create a great variation of the shapes, using the different parameters to control the shape and its aspect (radius, spikes, hardness, aspect ratio, angle and spacing).

The stroke of parametric brush is more sharpest and hard when we use hardness equal 1 when we compare with the raster brushes, is much easy to increase/decrease the softness via own editor or via Tool Options … instead the .gbr when we increase/decrease the hardness the stain is deformed by the blur algorithm how is possible in this gitlab issue: [Comparison test between hardness and Force with .gbr and .vbr brushes](https://gitlab.gnome.org/GNOME/gimp/issues/1081 "Issue #1081")

## How to combine parametric brushes and paint dynamics
I think is not possible have an unequivocal rule to combine brushes with paint dynamics, instead is possible to say that, in general: each paint dynamics represents an effect or a different technique.

<figure><img src="parametric-brushes.assets/parametric-brushes-mary-cassat-part-jag.jpg" width="640" title="Mary Casset pastel paint interpreted by Americo Gobbo" /><br><figcaption>Interpretation of Mary Cassat painting with pastel by Americo Gobbo. Dry Media paint dynamics with the brush set of parametric brushes.</figcaption></figure>

### Dry Media Experiments
I thought to begin with classic main dry media as pencil, crayon, charcoal and pastel.

I think that an unique dynamic is capable emulate practically all these dry medias. Is possible to identify many brushes, raster and/or parametric, that can be utilized with this paint dynamic … more opaque and darken is possible emulate charcoal and oil crayon … less opaque and lighter, the dry crayons and pencils.

Basically the paint dynamic emulates the technique and the brush emulates the stain quality and characteristics of the medium, but this is not always true, what I am saying is: that in certain cases some stain marks could be alone and without paint dynamics represents a good mark for a dry medium, but with limitations to use effectively to paint. In general, a good paint dynamics dedicated to a paint technique, e.g., dry media, it could work with many stain marks also with marks thought or pulled by another medium as watercolor, for instance.

To explore I have revised a bit the Pencil Generic Paint Dynamics
to adapt better it to other dry media and it is [here.](parametric-brushes.assets/parametric-brushes-Dry-Media.zip "Dry Media Paint Dynamics")

<figure><img src="parametric-brushes.assets/parametric-brushes-paintbrush-test.png" width="640" title="Parametric brush with Dry Media Paint Dynamics  - Paintbrush Tool" /><br><figcaption>Samples using Paintbrush tool with all parametric brushes of the set, shared on Download topic, using my paint dynamic Dry Media.</figcaption></figure>

<figure><img src="parametric-brushes.assets/parametric-brushes-airbrush-test.png" width="640" title="Parametric brush with Dry Media Paint Dynamics  - Airbrush Tool" /><br><figcaption>Samples with Dry Media Paint Dynamics using Airbrush tool with all parametric brushes of set shared on Download topic</figcaption></figure>

### Samples and Tests
Samples and tests are published in 2013 on my g+ account and, all are realized with my **Dry Media** Paint Dynamics.

* Testing to promote parametric brushes on GIMP. [See](https://plus.google.com/u/0/+AmericoGobbo/posts/PXvru8Rfumz)
* Comparison 1 of the dry media between parametric and raster brushes. [See](https://plus.google.com/+AmericoGobbo/posts/cLiZ6UZJ8w4)
* Comparison 2 between raster and parametric brushes with or not paint dynamics and different jitter values applied. [See](https://plus.google.com/+AmericoGobbo/posts/Jgv6q2o7Gee)
* Comparison 3 and conclusions about the behavior of paint dynamics for dry media  between parametric and raster brushes. [See](https://plus.google.com/+AmericoGobbo/posts/VHy2sNcteRK)

## Parametric Basic Brush Set
The idea to put in evidence these brushes is motivated by the real possibilities of the parametric brushes on GIMP to solve many issues of pictorial techniques with simple and dedicated paint dynamics.

This set contains the .vbr basic brushes, round and block (hard and soft versions). The 'BO' folder contains the .vbr basic brushes, round and block (hard and soft versions).

## Tool Options settings
To emulate better the dry media is necessary also some Tool Options setting conditions enabled.
* Enable the Dynamic Options > Fade > Use 100 and '%' unit.
* Enable the Jitter and use values between .5~1.0 circa.
* Incremental Option On.
* Force(1) at 100% (normally is 50% by default).
*(1)Only to GIMP 2.10 and 2.99 Devel.*

We have tested on GIMP 2.10, 2.99 and 2.8 with good results.

### Author, License and Download
The [Brush Set + Paint Dynamics](parametric-brushes.assets/parametric-brushes-Brushset-and-paint-dynamics.zip "Parametric Brush Set + Dry Media Paint Dynamics") was created by Americo Gobbo and licensed as Public Domain.
