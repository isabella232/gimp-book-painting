# Parametric Brush
Author: Americo Gobbo<br>
Date: 2018 June

<figure><img src="parametric-brushes.assets/parametric-brushes-personaggio-bizarro.jpg" width="640">
<figcaption><br>A fast sample made in 2013 by Americo Gobbo with Dry Media paint dynamics and parametric brushes.</figcaption>
</figure>

## The Parametric and Pictorial Techniques
The main scope of this article is to see the misused of parametric brush on GIMP and to demonstrate how is possible to use the parametric brush with paint dynamics to emulate many kind of media, for instance, the dry media.

On GIMP the brush set have a small amount of parametric brushes… why reason? Sincerely I do not know, perhaps, many illustrators, concept artists, photographers have been accustomed to see/utilize only raster brushes.

![](parametric-brushes.assets/parametric-brushes-dialog-editor.png "Image Title")<br>*Brush set and Parametric Editor*

The default shapes are round, square and diamond. Is also possible create a great variation of the shapes, using the different parameters to control the shape and its aspect (radius, spikes, hardness, aspect ratio, angle and spacing).

Some of advantages of parametric brushes are:
* The stroke of parametric brush is more sharpest and hard when we use hardness equal 1 than with the raster brushes,
* is much easy to increase/decrease the softness via own editor or via Tool Options … instead the .gbr when we increase/decrease the hardness the stain is deformed by the blur algorithm: [Comparison test between hardness and Force with .gbr and .vbr brushes](https://gitlab.gnome.org/GNOME/gimp/issues/1081 "Issue #1081")

### Dry Media Experiments
In 2013, I began study the dry media with parametric brushes, they are essentially the drawing tools as pencil, crayon, charcoal and pastel.
I have invited also Gustavo Deveze to use my parametric brush set with 2 paint dynamics dedicated exclusively to dry media.
...

<figure><img src="parametric-brushes.assets/parametric-brushes-deveze-dry-media-test.png" width="640" title="Dry Media by Gustavo Deveze" /><br><figcaption>Gustavo Deveze drawing with the Dry Media paint dynamics with the brush set of parametric brushes.</figcaption></figure>

#### Paintbrush and Airbrush Tool
To explore the dry media effects with parametric brushes, I have revised, initially in 2013, the Pencil Generic Paint Dynamics to adapt better it to other dry media.
After to work much with the variations of Pencil Generic... I have found a good compromise, but the methodology was complex and based only on trial and error.

> I have thought interesting to understand better the real media and to try a way to modeling the effects via paint dynamic making a good screening of real variables on these media, the is demonstrated good to modeling the first steps or the main aspects of this media. This methodology I will describe in another article.

I have verified, also, that is possible to use different tools, pencil, paintbrush and airbrush, but, effectively the airbrush is more interesting, mainly of the Rate and Flow controls.

<figure><img src="parametric-brushes.assets/parametric-brushes-dry-media-airbrush-x-paintbrush.png" width="" title="Parametric brush with Dry Media Paint Dynamics  - Paintbrush Tool versus Airbrush Tool" /><br><figcaption>Samples using round parametric brushes of the set with my paint dynamic Dry Media.</figcaption></figure>

In general, all size brushes are working well, but mainly between 8 ~ 64 pixels is the better compromise. The large brushes are interesting to covering large areas and is not possible to have a good shape, they are appearing a bit soft.

## Parametric Basic Brush Set and Paint Dynamics | Download
The brush set, in 'B0' folder, contains the .vbr basic brushes, round and block (hard and soft versions). The paint dynamics are two: for the graphics tablet's stylus with tilt and not. The version with tilt is fun to use and is possible to emulate well the effect when you are inclining the tool in the real cases.

Download [Brush Set + Paint Dynamics](parametric-brushes.assets/parametric-brushes-Brushset-and-paint-dynamics.zip "Parametric Brush Set + Dry Media Paint Dynamics").

## Tool Options Settings
To emulate better the dry media I recommend to use Airbrush Tool with this setting conditions on Tool Options:
* Opacity 75 ~ 100
* Enable the Jitter and use values between 0.5 ~ 0.75 circa.
* Force(¹) at 100% (normally is 50% by default).
*(¹)Only to GIMP 2.10 and 2.99 Devel.*

We have tested on GIMP 2.10, 2.99 and 2.8 with good results.

### Author, License
Created by Americo Gobbo and licensed as Public Domain.
