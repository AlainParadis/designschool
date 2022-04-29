---
layout: submission
type: assignment
formsum: formative
sortorder: 3.2
appsused: psd, indd
title: "Spot Colour Channels"
level: undetermined
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=236882&grpid=0&isprv=0&bp=0&ou=279810"
submission: "indesign-package"
links: |
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/printing-spot-colors.html" target="_blank" title="Spot Colour Channels">Spot Colour Channels</a>
downloads: "https://www.dropbox.com/s/ytj4i1yf2m9ydux/photoshop-spot-colour-channels.zip?dl=1"
description: "At times, four colour process printing can be quite bland. There are times when you want a more crafted printed piece with more accurate colours and more punch. This is where spot colour printing can come to the rescue."
details: |
  ### The Context
  This is an ad for a home renovation company, using our two spot colours. Every element in this ad is either black or in Pantone 165. The first frame shows the black content of the ad in InDesign. The second is all the orange 165 content. The third plate shows the colour composite.

  <img class="size100" alt="spot-colour-reno-ad" src="/images/photoshop-spot-colour-channels/spot-colour-reno-ad.jpg">

  The ad is an InDesign document, but it contains graphics from Illustrator (the logo) and Photoshop (the photo). No matter which application produced the artwork, it needs to be either in black or in our spot colour.

  The difference with this print job and a four colour process job is that only two printing plates are produced rather than four. Less ink is used. It's run on a smaller, two-colour press. A job like this could be given to a small printer who possibly charges less than a large operation.

  <div class="attentionbox tip">
    The big advantage with a spot colour print job is that the colours reproduce way more accurately. They can also be more intense.
  </div>

  To apply our spot colour to the artwork, we need to first add the swatches in the Swatches panel in both InDesign and in Illustrator. The process is different in Photoshop. In the InDesign document, go to your Swatches panel menu. Choose New Swatch....

  <img class="size100" alt="indesign-ad-spot-swatch" src="/images/photoshop-spot-colour-channels/indesign-ad-spot-swatch.jpg">

  Do the same thing in Illustrator.

  Select each piece of artwork in the InDesign document and in the Illustrator document. Apply the approriate spot colour to each. What's orange needs to be in Pantone 165 C. What's black needs to be in the regular black swatch you have in your Swatches panel.

  While you're at it, delete all the other swatches in the panel.

  #### Spots in Photoshop

  Every Photoshop image has one or more channels, each storing information about colour elements in the image. The number of default colour channels in an image depends on its colour mode. For example, a CMYK image has four channels, one each for cyan, magenta, yellow, and black information. Think of a channel as analogous to a plate in the printing process, with a separate plate applying each layer of colour. Spot colour channels are used to add spot colour plates for printing.

  <img class="size100" alt="channels-panels" src="/images/photoshop-spot-colour-channels/channels-panels.jpg">

  Convert the provided image to greyscale without merging layers. Now you can add a new spot colour channel with Pantone 165 C. 

  <img class="size100" alt="spot-channels-art-done" src="/images/photoshop-spot-colour-channels/spot-channels-art-done.jpg">

  Use Cut and Paste to transfer pixels from the greyscale channel to the orange channel. Turn off all but the background layer's visibility. Hit the D key to set your swatches to the default black and white. Select, then cut and paste it onto our new orange channel.

  #### Punching a Hole in Spot Colours

  Spot colour channels are usually displayed in greyscale. The darker the content, the more intense the application of the spot colour.
  
  You’ll notice that there is a second layer in the file named Hammer. Turn on its visibility. Notice that the hammers are covered with orange. To reveal the hammers, simply draw a marquee which covers the hammers. Target the Pantone 165 C channel. Fill with white.

  When you fill with white on a Spot Colour Channel, it erases the spot colour in the canvas.

  Now the hammers should appear in greyscale (with no orange). They will print on the black plate when colour separated.

  #### Full Intensity Spot
  
  Now we will show how filling with black on the Spot Channel actually applies 100% of the Spot Colour in the canvas.

  1. Draw a Marquee in the small area to the right of the hammer.
  2. Target the Spot Colour Channel
  3. Fill with black. See? It fills with solid Orange 165.

  #### Screening a Spot

  Now, create a screen of the orange 165 colour.

  1. Use your Marquee tool to make a slection to the left of the hammer.
  2. Hit the “D” key to reset your colour swatches to black and white.
  3. Go to the Colour panel. Enter a value of 20%.
  4. Target the Spot Colour Channel.
  5. Fill with the Foreground Colour (20% black)

  20% black on the orange spot colour channel will print a 20% screen of Pantone 165 C.

  #### Type on Spot Channels

  Type works very differently on spot colour channels, compared to normal type in Photoshop. To start with, it is not vector data. These means that it is way less editable. It also means that there are no font file dependancies with such a file. Let’s try.

  1. Target the Spot Colour Channel.
  2. Hit the “D” key to reset your foreground and background colours to black and white.
  3. Type the word **WORK**.
  4. Hit Enter to accept what you typed. Your text is loaded in a marquee which you can move around while the Marquee tool is active.
  5. Once you deselect, you can no longer edit the text. It is painted in Pantone 165.

  We’re Done! Save this file as a native PSD. Go to InDesign to replace the linked CMYK file with the 2 colour file. You can check your colour break using the Separations Preview panel. Go <span class="command">Window > Output > Separations Preview</span>. Turn off the visibility of all but the black and orange plates. Your ad content should all still be showing on screen.

  When you print seps, the file would separate into a black plate and a Pantone 165 plate.

  ### Bump (or Kiss) Plates

  Spot colours are not only used in spot colour printing. They can also be used to augment a four colour process print job.

  <img class="size100" alt="kiss-plate" src="/images/photoshop-spot-colour-channels/kiss-plate.jpg">

  You've seen this before, even if you didn't notice. That advertisement for makeup where the lipstick on the model looks more intense than the rest of the inks in the ad. They've likely printed the whole ad in CMYK, then they printed a spot colour only on her lips.

  ### Varnish Plate

  The same technique is also used to add a varnish to a photo in Photoshop. Add a spot colour (of any colour), then name it Varnish. This will produce another plate at the printer's with which they will print the spot varnish over only those areas of the image.

  <img class="size100" alt="spot-varnish" src="/images/photoshop-spot-colour-channels/spot-varnish.jpg">

  The man in the photo is looking pretty yellow. He's not going to print that way. That's our spot colour plate we created to contain the coverage for the spot varnish. The varnish will be applied where the black coverage is in the photo on the right.

  <div class="attentionbox achtung">
    It's important that the fill on your spot varnish channel is set to 100% black. We don't screen varnishes.
  </div>

  ### Printing Separations

  Let's output our ad to a colour-separated PDF file. Go File > Print...

  <img class="size50" alt="seps-print-dialogue" src="/images/photoshop-spot-colour-channels/seps-print-dialogue.jpg">

  When you click save, it's going to produce a PostScript (.ps) file. Open it with Preview.app. You'll see that you have 5 pages. Save it as a PDF file in your project folder.

  <figure>
      <img class="size100" alt="printed-seps" src="/images/photoshop-spot-colour-channels/printed-seps.jpg">
  <figcaption>
    Colour separations: All the content in the ad prints either on the black or the orange plate.
  </figcaption>
  </figure>
  There's a plate for each of cyan, magenta, yellow, black and Orange 165 C. The first three should have no content on them. When I have a spot colour job, I actually print these on paper. I write on the pages Doesn't Print and Prints 165C. There will be no excuses if something goes arwry at the printer's. You've covered your bases.
assignment: |
  Convert the provided photoshop file to Black plus Pantone 1817C.

  <figure>
      <img class="size100" alt="spot-colour-channels-summative" src="/images/photoshop-spot-colour-channels/spot-colour-channels-summative.jpg">
  <figcaption>
    This image shows the colour break for your file.
  </figcaption>
  </figure>

  There are guides in the Photoshop file to help you line things up.

  Once you're done, place the ad in the provided InDesign document. Make sure to check the Separations Preview panel to make sure the colour break is correct.
---
