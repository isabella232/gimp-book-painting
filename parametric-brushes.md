# Parametric Brush
Author: Americo Gobbo<br>
Date: 2018 June


<figure>
<img src="parametric-brushes.assets/parametric-brushes-personaggio-bizarro.jpg" width="640">
<figcaption>A quick sample made in 2013 by Americo Gobbo with Dry Media paint dynamics and parametric brushes.</figcaption>
</figure>

## The Parametric Brush and Painting Techniques
It seems artists haven't yet realized the full usefulness and versatility of GIMP's parametric brushes, especially when paired with the proper dynamics. This article shows how to use parametric brushes to create convincing emulations of dry media such as pencil, color pencil, charcoal, chalk and pastel.

<figure>
<img src='parametric-brushes.assets/parametric-brushes-dialog-editor.png' alt='Image Title'>
<figcaption>
Brush set and Parametric Editor
</figcaption>
</figure>

The default shapes are round, square and diamond. It's also possible create a large variation of the shapes, using the different parameters to control the shape and its aspect (radius, spikes, hardness, aspect ratio, angle and spacing).

Some of the advantages of parametric brushes are:

* The stroke of the parametric brush is sharper and harder when we use hardness equal to 1 (compared to raster brushes)
* It's much easier to increase/decrease the hardness via editor or Tool Options (the .gbr and .gih brushes, when we increase/decrease the hardness, is deformed by the blur algorithm: [Comparison test between hardness and Force with .gbr and .vbr brushes](https://gitlab.gnome.org/GNOME/gimp/issues/1081 "Issue #1081"))

### Dry Media Experiments
In 2013 I began to study the emulation of dry media with parametric brushes (these are essentially the drawing tools such as pencil, crayon, charcoal, and pastels).
I also invited Gustavo Deveze to use my parametric brush set with 2 paint dynamics dedicated exclusively to dry media.

<figure><img src="parametric-brushes.assets/parametric-brushes-deveze-dry-media-test.png" width="640" title="Dry Media by Gustavo Deveze" /><br><figcaption>Gustavo Deveze drawing with the Dry Media paint dynamics with the brush set of parametric brushes.</figcaption></figure>

#### Paintbrush and Airbrush Tool
To explore the dry media effects with parametric brushes, I have revised, initially in 2013, the Pencil Generic Paint Dynamics to adapt it better to other dry media.
After working with variation of the Pencil Generic Dynamics I found a good compromise, but the methodology to get there was complex and based on trial and error.

> I have thought interesting to understand better the real media and to try a way to modeling the effects via paint dynamic making a good screening of real variables on these media, the is demonstrated good to modeling the first steps or the main aspects of this media. This methodology I will describe in another article.

I have also verified that it's possible to use different tools, pencil, paintbrush and airbrush, but the airbrush is more interesting, mainly due to the Rate and Flow controls.

<figure>
<img src="parametric-brushes.assets/parametric-brushes-dry-media-airbrush-x-paintbrush.png" width="" title="Parametric brush with Dry Media Paint Dynamics  - Paintbrush Tool versus Airbrush Tool" />
<figcaption>Samples using round parametric brushes of the set with my paint dynamic Dry Media.</figcaption>
</figure>

In general, all size brushes are working well, but mainly between 8 ~ 64 pixels is the best compromise. The large brushes are interesting to cover large areas but at that size they appear a bit soft.

## Parametric Basic Brush Set and Paint Dynamics | Download
The brush set, in 'B0' folder, contains the .vbr basic brushes, round and block (hard and soft versions). There are two paint dynamics: for the graphics tablet's stylus with tilt and not. The version with tilt is fun to use and it's possible to emulate well the effect when you are inclining the tool in the real cases.

Download [Brush Set + Paint Dynamics](parametric-brushes.assets/parametric-brushes-Brushset-and-paint-dynamics.zip "Parametric Brush Set + Dry Media Paint Dynamics").

## Tool Options Settings
To best emulate dry media I recommend using the Airbrush Tool with these settings on Tool Options:
* Opacity 75 ~ 100
* Enable the Jitter and use values between 0.5 ~ 0.75 circa.
* Force¹ at 100% (normally is 50% by default).  
  ¹ Only on GIMP 2.10 and 2.99 Devel.

<figure><img src="" width="" title="Tool Options Settings" /><br><figcaption>Airbrush, my proposal of the settings to the dry media effects.</figcaption></figure>

We have tested on GIMP 2.10, 2.99 and 2.8 with good results.

### Author, License
Created by Americo Gobbo and licensed as Public Domain.

### Acknowledgements
