---
layout: default-nav
type: card
formsum: formative
sortorder: 4.4
appsused: psd
title: "Intro to Layer Masks"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=84512&grpid=0&isprv=0&bp=0&ou=92671"
submission: "generic-zip-folder"
links: |
  - <a href="https://helpx.adobe.com/photoshop/using/masking-layers.html" target="_blank" title="Adobe: Mask Layers">Adobe: Mask Layers</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLDXxSkeR7f0X8DmBp0hlEaj"
downloads: "https://www.dropbox.com/s/50uqa0oa0wiq2xp/photoshop-intro-to-layer-masks.zip?dl=1"
description: "Layer Masks are arguably the most powerful, most frequently used tool in the whole Photoshop universe. We'll create pixel-based Layer Masks to achieve different results."
details: |
  Layer Masks are used to:

  * Erase (mask) areas of a photo.
  * Select an area of a photo to apply an effect.
  * Apply Adjustment Layers selectively.
  * Combine photos in one canvas.
  * ...and much, much more.

  <figure>
    <img class="size50" alt="layers-panel-mask-icon" src="/images/photoshop-intro-to-layer-masks/layers-panel-mask-icon.jpg">
  <figcaption>
    Whenever you have an icon in the second column in your layers panel, that's a mask.
  </figcaption>
  </figure>

  <div class="attentionbox tip">
    The benefit of using a mask is that it's part of a non-destructive workflow in Photoshop. The alternative would be to erase pixels, rather than hiding (or masking) them, which is never advisable.
  </div>

  ### Important Keyboard Commands

  * d = Default colours in foreground/background swatches.
  * x = Swap foreground/background swatches.
  * ⌥-delete = Fill with foreground colour
  * ⌘-delete = Fill with background colour.
  * ⌘-a = Select all.
  * ⌘-d = Deselect all.
  * Shift-⌘-i = Invert selection.
  
  ## Raster Layer Masks

  A raster layer mask is a greyscale image, where darker pixels hide the underlying photo to increasing degrees. It works a bit like a dimmer on a light switch. The darker the pixels are on the mask, the less you can see the photo on that layer.

  <figure>
      <img class="size100" alt="photoshop-layer-mask-example" src="/images/photoshop-intro-to-layer-masks/photoshop-layer-mask-example.jpg">
  <figcaption>
  On a mask, darker the gradient gets, the more the photo will be hidden.
  </figcaption>
  </figure>

  You can mask content by:

  1. creating a mask, then painting with black, white or grey.
  2. creating a selection, then creating a mask.

  There are more techniques for creating masks, but these two will get you started.

  ### Simple Mask

  Lets start with replacing the background on a photo by hiding the original one to reveal the one on the layer below. In this case, we'll change the background to a beach scene.

  <img class="size100" alt="photoshop-layer-masks-simple-mask" src="/images/photoshop-intro-to-layer-masks/photoshop-layer-masks-simple-mask.jpg">

  You can use Select & Mask to refine your mask's edge. Simply double-click on the mask's icon in the Layers panel to access it.

  <figure>
      <img class="size100" alt="photoshop-select-and-mask" src="/images/photoshop-intro-to-layer-masks/photoshop-select-and-mask.jpg">
  <figcaption>
  <ol>
  	<li>Refine Edge tool</li>
  	<li>Choose preview mode</li>
  	<li>Set auto edge detection</li>
  	<li>Sharpen or feather edges</li>
  	<li>Set how to output new mask</li>
  </ol>
  </figcaption>
  </figure>

  Use the Refine Edge tool to paint along the edge. Photoshop will detect edges, then try to guess how to enhance the selection.

  ### Masking to Blend Photos

  We can also use masks to blend photos. We'll use the Gradient Tool on the mask. Since black hides and white reveals, this will make the photo on the top layer gradually become transparent to partially reveal the photo below.

  <img class="size100" alt="photoshop-layer-masks-gradient-mask" src="/images/photoshop-intro-to-layer-masks/photoshop-layer-masks-gradient-mask.jpg">

  <div class="attentionbox tip">
    A black to white gradient replaces itself each time to drag one. A black to transparent gradient adds to itself each time you drag one.
  </div>

  ### Masking with a Photo

  <img alt="photoshop-paste-on-a-mask" src="/images/photoshop-intro-to-layer-masks/photoshop-paste-on-a-mask.jpg" class="size100">

  A Layer Mask is a greyscale image. Where the pixels are dark on the mask, they're hiding whatever's on the layer below. Where they're light, they reveal what's on the layers below. It stands to reason that if we paste a photo onto a mask, it will do the same, hopefully giving us interesting results.  

  ### Bonus Technique

  We'll use content from two stacked layers to take the best elements from each photo. In the end, everyone will have a smile on their faces. We'll use Auto-Align Layers and Layer Masks to accomplish this. You'll see; it's pretty cool. 

assignment: |

  ### Simple Mask

  Mask the background, with the help of the Select & Mask feature, if needed.

  <img class="size100" alt="layer-masks-simple-mask-summative" src="/images/photoshop-intro-to-layer-masks/summative-simple-mask-summative.jpg">

  Don't Save As... or rename the file. Just Save, then close it.

  ### Masking to Blend Photos

  Use a gradient on a mask to blend the road into the forest.

  <img class="size100" alt="summative-gradient-on-a-mask" src="/images/photoshop-intro-to-layer-masks/summative-gradient-on-a-mask.jpg">

  ### Masking with a Photo

  Use the provided Ink Blot layer to mask the panorama. Remember that <span class="command">⌘-i</span> inverts colours.

  <img class="size100" alt="summative-paste-onto-a-mask" src="/images/photoshop-intro-to-layer-masks/summative-paste-onto-a-mask.jpg">

  ### Bonus Technique

  Using a layer mask, make the two woman's eyes work best for the photo.

  <img class="size100" alt="summative-replace-eyes" src="/images/photoshop-intro-to-layer-masks/summative-replace-eyes.jpg">
---
