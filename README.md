# rf3a
Content to assist in practicing F3A in realflight 

![alt text][f3a]


# Background

My in-real-life F3A loops are too narrow - so what I am doing wrong, and what should a loop look like? To try and better understand my positioning in 3D space, I thought I'd build some F3A-shaped train-tracks to fly through in realflight. And with this repository, I thought I'd inflict this crazy idea on fellow F3A pilots too - in the hope that it is useful.

# Loop track design

I've competed in a couple of F3A clubman events in the UK, but the schedule is pretty consistent worldwide. [Here's our guidance](http://www.gbrcaa.org/?page_id=84).

Here's the side view of the loop track. The loop to the right is the pre-sequence turnaround and out of the box (box not shown).

![alt text][looptrack]

## expectation management
this is a rush job, and not well packaged, explained, or set up for anything other than exactly my RF8 version. Do as you will with it, but I am currently unable to provide support (feel free to raise issues in case others can help). I will progress this again in due course, but work's, ahem, a bit busy.

# Content

## 3dsmax 
The raw loop tracks, made with a spline that is swept with a bar.

[this advice still holds for 2018](https://www.knifeedge.com/forums/index.php?threads/new-import-capabilities-for-rf-8.33293/):

```
I am using a 1024 X 1024 targa (.tga) image, color, 8-bit. I have exported it from Photoshop as a 16, 24 and 32 bit image. They all say 8 bit per channel color.
In 3DSM, in Slate Material Editor, I took a bitmap from Materials, Maps, General and browsed to the image file. I then took a Standard Material from Materials>Scanline>Standard. I connected the bitmap output to the diffuse color input of the Material. I then selected my object and selected apply material to selection

```

Note comments from F3A folks particularly welcome on the proportions of the loop tracks and usage of the box

## realflight

### scenery

The loop track as scenery. To import into your Realflight, put ```f3a_vc.FBX```and ```redCS.tga``` file in the same place, and import into realflight.

### airport

Mind the zombie! I tried different size loop tracks, but haven't settled on which is best size for Sportsman.

### airplane

Many thanks to boof69 for their work on an F3A plane. [original here](https://www.knifeedge.com/forums/index.php?resources/aj-spark-evo-ii_ea.17551/)
I reckon it needs a bit of fettling, but the version in this repository is not there yet. The chin hatch stays on now, though, and I added tight smoke.

## img

Here's a GIF of me flying - note the use of the nose camera to assess alignment. Waaaaaaaaaaay too much info to take in - I can either fly FPV or LOS not both at once - so not currently able to put together a schedule in these loop tracks.

# Conclusion
Enjoy! Open PR with mods 

 
[f3a]: ./img/F3A.gif "Flying in the F3A frame"
[looptrack]: ./img/looptrack.PNG "F3A sportsman sequence"