---
layout: submission
type: assignment
formsum: formative
sortorder: 3.1
appsused: psd, indd
title: "Duotones"
level: cg3
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=162712&grpid=0&isprv=&bp=0&ou=193261"
submission: "indesign-package"
links: |
  - Lynda: <a href="https://www.lynda.com/Photoshop-tutorials/Duotone/533301/582605-4.html" target="_blank" title="Lynda: Duotones">Duotones</a>
  - Behance: <a href="https://www.behance.net/search?search=duotone" target="_blank" title="Examples of Duotones">Examples of Duotones</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLDfiqtRsavncYqJWoHnEjRy"
downloads: "https://www.dropbox.com/s/9zbqkz0k6s437kx/photoshop-duotones.zip?dl=1"
description: "A duotone Photoshop image is a greyscale image printed with a coloured ink rather than with black ink. You can obtain striking results with a well thought-out production strategy."
details: |
  ### About Channels

  #### Channels in RGB

  Despite Photoshop's awesome colour manipulation capabilities, it's actually colour blind. It really only understands greyscale images. An image is composed of three stacked greyscale images called channels. The lighter the grey on the Red channel, the more intense the red will be in your photo.

  <figure>
  <img class="size100" alt="duottone-channels-rgb" src="/images/photoshop-duotones/duotones-channels-rgb.jpg">
  <figcaption>
  You can see in the image above that the darker the pixels on a given channel, the *less* intense that colour is in your photo. It's like the light's are out over that part of the image.
  </figcaption>
  </figure>

  #### Channels in CMYK

  The very definition of a CMYK image is that it has four channels. One for each of Cyan, Magenta, Yellow and Black. Everything else being equal, CMYK files are larger than RGB files for that reason.

  <figure>
    <img class="size100" alt="duotone-channels-cmyk" src="/images/photoshop-duotones/duotones-channels-cmyk.jpg">
  <figcaption>
    Channels work the same way in CMYK, except the light values are reversed. The printer will lay down more ink where the channel is dark.
  </figcaption>
  </figure>

  ### Why a Duotone?

  A duotone is a Photoshop greyscale image printed with a spot colour ink. There are a few reasons to use a duotone.
    <figure>
  <img class="size100" alt="duotones-compare-to-greyscale" src="/images/photoshop-duotones/duotones-compare-to-greyscale.jpg">
  <figcaption>
    You can see in the image above that the duotone on the righ is much more interesting than the greyscale image on the left.
  </figcaption>
  </figure>

  You may be printing a two spot-colour job. In this case you can apply both of your inks to a photograph rather than just printing it in greyscale. Be aware that this may not always yield great results, depending on the ink combination you're using.

  ### Creating a Duotone

  The first step in creating a duotone image is to convert it to greyscale mode. You can simple use Image > Mode > Greyscale. This won't give you any control of the conversion process.

  If you do want to adjust the tonality of your photo as you convert it, it's better to start with a Black & White adjustment layer first.

  <figure>
    <img class="size100" alt="duotones-compare-greyscales" src="/images/photoshop-duotones/duotones-compare-greyscales.jpg">
  <figcaption>
    You can see that the right side of the photo has richer tones, due to the Red Filter black & white setting that's applied to that half of the photo. It's superior to the flatter part of the photo on the left, which is a normal greyscale conversion.
  </figcaption>
  </figure>

  Once we have the adjustment layer set, we can then use Image > Mode > Greyscale to convert the image.

  <figure>
    <img class="size100" alt="duotones-convert-to-greyscale" src="/images/photoshop-duotones/duotones-convert-to-greyscale.jpg">
  <figcaption>
    Convert to greyscale and flatten.
  </figcaption>
  </figure>

  Once you convert to greyscale, you'll end up with a flattened photo in the Layers panel. You'll also notice that there's only one Gray channel in the Channels panel.

  <figure>
  <img class="size100" alt="duotones-make-duotone-green" src="/images/photoshop-duotones/duotones-make-duotone-green.jpg">
  <figcaption>
    This image offers a before & after comparison between the greyscale and duotone mode areas.
  </figcaption>
  </figure>

  #### Editing Duotones

  After you've created a duotone image, it is possible to edit how the inks are mapped across the photo.

  <figure>
    <img class="size100" alt="duotones-edit-duotone-curves" src="/images/photoshop-duotones/duotones-edit-duotone-curves.jpg">
  <figcaption>
    All you need to do to edit your duotone curves is to go back to Image > Mode > Duotone... Click on one of the curve icons to edit it.
  </figcaption>
  </figure>

  In this photo, the press will print this photo with black ink, then it will print Pantone 349 CVC on top of the black. The distribution of inks is based on each colour's curves.

  ### Using Duotones

  If you place your duotone mode file in InDesign, you can see the colour break with the Colour Separations panel.

  <figure>
  <img class="size100" alt="duotones-in-indesign" src="/images/photoshop-duotones/duotones-in-indesign.jpg">
  <figcaption>
    A duotone image placed in InDesign. You can see how the two colours contribute to the photo from the Separations Preview panel.
  </figcaption>
  </figure>

  ### Faux Duotones

  These images have he appearance of a duotone, but are really in full colour. All you need to do is open your RGB image in Photoshop, then add Black & White adjustment layer to it.

  <figure>
    <img class="size100" alt="duotones-fake-duotone" src="/images/photoshop-duotones/duotones-fake-duotone.jpg">
  <figcaption>
  In the Black & White adjustment layer's Properties panel, you can edit the tint of the image to get the desired effect.
  </figcaption>
  </figure>

  This is a faux duotone. As you can see, the Channels panel still shows the image is in RGB. It has three channels rather than the one a duotone image would have.
assignment: |
  You're going to convert each of the provided photos to a true duotone mode. Make a faux duotone with the second version of the photo.

  <figure>
  <img class="size100" alt="01-duotone-real" src="/images/photoshop-duotones/01-duotone-real.jpg">
  <figcaption>
    This is a real duotone. It has a single channel. Choose the colour you want. Ajust the curves as you see fit.
  </figcaption>
  </figure>

  <figure>
  <img class="size100" alt="02-duotone-fake" src="/images/photoshop-duotones/02-duotone-fake.jpg">
  <figcaption>
    This is a faux duotone. It's still in RGB colour mode. Add a Black and White adjustment layer. Use the colour of your choice. Adjust the curves as you see fit.
  </figcaption>
  </figure>

  <figure>
  <img class="size100" alt="03-duotone-real" src="/images/photoshop-duotones/03-duotone-real.jpg">
  <figcaption>
    This is a real duotone. It has a single channel. Choose the colour you want.
  </figcaption>
  </figure>

  <figure>
  <img class="size100" alt="04-duotone-fake" src="/images/photoshop-duotones/04-duotone-fake.jpg">
  <figcaption>
    This is a faux duotone. It's still in RGB colour mode. Add a Black and White adjustment layer. Use the colour of your choice.
  </figcaption>
  </figure>
---
