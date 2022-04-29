---
layout: default
type: informational
formsum:
sortorder:
appsused: indd, pdf, ai
title: "Trapping"
level: info
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=86419&grpid=0&isprv=0&bp=0&ou=92653"
submission:
links: |
  - Adobe: <a href="https://helpx.adobe.com/illustrator/using/trapping.html" target="_blank">Trapping</a>
downloads: "https://www.dropbox.com/s/2scolofucbf6zm6/illustrator-trapping.zip?dl=1"
description: "While designers shouldn't need to do trapping on their files, they should be familiar with the concept and the mechanics of how it works."
details: |
  ### Why Trapping?

  While I was eating my Cap'n Crunch cereal this morning, I found myself entranced by the artwork on the box. I was focused on a small area of the front. I noticed that where two contrasting colours met, they seemed to overlap to create a darker colour band all along that intersection. 

  <figure>
    <img class="size75" alt="trapping-capn-crunch" src="/images/illustrator-trapping/trapping-capn-crunch.jpg">
  <figcaption>
    It's difficult to make out, but one of the dark strokes we see in the image is the blue and the red inks overlapping.
  </figcaption>
  </figure>
  Cereal boxes are printed with a unique printing method called Flexography. This is a lower-cost printing method that excels at printing large areas of solid colour.

  This blue ink and red ink are each spot colours. They have no colour in common. So, if registration were off on the press, there would be a risk that an unisightly gap could appear between the shapes.

  This happens because inks with no colours in common knock out of each other. In the image below, if you were to remove the yellow circle, there would be a hole in the cyan square. When do colours knock out? When they don't have an ink in common.

  <figure>
    <img class="size100" alt="Trapping required, yes" src="/images/illustrator-trapping/trapping-required-yes.svg">
  <figcaption>
  Because the two shapes have no colours in common, trapping is needed. The yellow will be spread over the cyan.
  </figcaption>
  </figure>
  Above, on the right, we have pure yellow and pure cyan. They have no colours in common. This means that the cyan square prints with a hole in it. They yellow is then printed to fit the hole. Therein lies the problem. The yellow will almost never line up perfectly with the hole. This is why we need trapping.

  <figure>
  <img class="size100" alt="Trapping required, no" src="/images/illustrator-trapping/trapping-required-no.svg">
  <figcaption>
  In this case, there is cyan in common over all the artwork, so no trapping is needed.
  </figcaption>
  </figure>
  Above, on the left, both shapes contain some cyan. The green circle contains 30% cyan. You can see that when the cyan is printed, there is no hole in it. Then yellow is simply printed on top. There's no opportunity for a gap between the shapes.

  Trapping on large printed surfaces with a poor quality printing process like the cereal box make the overlap visible to the naked eye. You often see the same effect on packaging. Trapping shouldn't be visible to the naked eye with higher quality printing.

  <div class="attentionbox achtung">
    In real life, trapping is the responsibility of the printer. You actually should never perform trapping on your own files. The reason is, to trap your files, you would need specialized software and very specific technical information on the stock and presses used to produce your work. What we're doing today, is learning the mechanics of trapping, so you understand what the printer is doing with your designs before they go to press.
  </div>

  ### How Trapping Works

  <img class="size75" alt="trapping-example" src="/images/illustrator-trapping/trapping-example.svg">

  <div class="attentionbox tip">
    Whether it's a choke or a spread, it's the light colour that expands.
  </div>

  There are a few settings that can affect the intensity of the trap. There's the weight of the stroke and the tint reduction. The weight of the stroke is pretty obvious. The weight of the stroke dictates the size of the overlap of the light colour on top of the dark colour. Tint reduction is how *faded* the lighter colour is where it overlaps with the darker one.

  ### Creating a Trap


assignment: |
  <img class="size75" alt="Trapping" src="/images/illustrator-trapping/trapping-exercise.svg">

  Create a trap on provided artwork by adding an overprinting stroke. You'll need to choose which shape to add the stroke to. Add a 4 point stroke. It needs to be the same colour as the shape it's on.

---
  
  <a href="https://helpx.adobe.com/indesign/using/adjusting-ink-options-trapping.html#adjusting_ink_neutral_density_values" target="_blank">Useful Link</a>.

https://www.lynda.com/Illustrator-tutorials/Trapping-object-overprint-stroke/733/43435-4.html

  When objects touch each other that don't have colours in common.
  If registration is off, an ugly gap is created.
  Combine the two colours so the gap is eliminated.
  We don't do this manually. The RIP does it.
    What is a RIP: Raster Image Processor
    Converts image to raster
    The result is a plate for each colour.
  The dark area always defines the shape.

  When do you need a trap?

  ## Overprinting

  ## Trapping Scenarios

  CMYK next to a spot colour.
  Two different process colours
  Two different spot colours
  Two process mixes with no colours in common.

  Add a stroke as the same spot colour as the fill.
  In Attributes panel, turn on Overprint Stroke.
  Turn on Overprint Preview to see the effect.
