---
layout: submissions
type: card
formsum: formative
sortorder: 2.0
appsused: psd
title: "Blending & Masking"
level: none
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=120805&grpid=0&isprv=0&bp=0&ou=145571"
links: 
video: 
downloads: "https://www.dropbox.com/s/kni4vuo621s5fcz/photoshop-double-exposure-effect.zip?dl=1"
description: "This effect has been trendy for a while now. Notwithstanding the trend, the effect makes use of important features in Photoshop."
details: | 
  ## The Double Exposure Effect

  The double exposure effect has been very popular of late. The trend will most certainly fade, but the exercise of creating the effect has valuable techniques which can be applied in varied circumstances.

  This is how <a href="https://en.wikipedia.org/wiki/Multiple_exposure" title="Wikipedia's definition of the Double Exposure effect." target="_blank">Wikipedia</a> defines the effect:

  > In photography and cinematography, a multiple exposure is the superimposition of two or more exposures to create a single image, and double exposure has a corresponding meaning in respect of two images."

  We'll be using two images to create an original and creative composition.

  You can peruse some examples of <a href="https://duckduckgo.com/?q=double+exposure+photography&amp;t=osx&amp;iax=1&amp;ia=images" title="Double Exposure effect examples" target="_blank">the double exposure effect that's become so popular here</a>.

  ## Source Images

  We need two types of photos. One portrait of an individual. It's best to either have a white background on the portrait. The second is an outdoor scene. The source photos play a large role in the final effect. The more you practice with the effect, the more you'll be able to predict the outcome.

  <img class="size75" alt="photoshop-double-exposure-both-photos" src="/images/photoshop-double-exposure/photoshop-double-exposure-both-photos.jpg">

  Once you've practiced the technique enough that you undestand the mechanics of it, you can experiment with different content, like architectural photos and others.

  ## Technique #1: Paste Onto a Mask

  The most basic method for achieving the double exposure effect is to simply paste the portrait onto the mask on the scene's layer. Just <span class="command">⌘-A</span> select all to copy the portrait. Add a layer to the scenery layer. <span class="command">⌥-click</span> on the mask, then paste. Voilà. You have your most basic double exposure effect.

  <img class="size75" alt="photoshop-double-exposure-1" src="/images/photoshop-double-exposure/photoshop-double-exposure-1.jpg">

  This is the result of a simple copy/paste onto a mask. The photo's colours were also inverted <span class="command">⌘-I</span>. We did this because the portrait has mostly dark content. On a mask, white pixels reveal, so invert the mask's colours if needed.

  You can see that a new white layer was added as a background to the composition.

  You can make further selective enhancements by creating a duplicate of the portrait on top of the whole layer stack. Set its blend mode to Multiply. Add a mask to the portrait layer. Use a large soft brush to paint black gently on passive areas of the photo.

  <img alt="photoshop-double-exposure-paint-on-mask" src="/images/photoshop-double-exposure/photoshop-double-exposure-paint-on-mask.jpg">

  If needed, increase the contrast on the whole composition with a Levels adjustment layer.

  <img alt="photoshop-double-exposure-gradient-map" src="/images/photoshop-double-exposure/photoshop-double-exposure-gradient-map.jpg">

  Add Gradient Map adjustment layer to colour the composition.

  With some experimentation with various photos, you'll see that you can achieve pretty great results.

  This technique may not give you the control you want. The following technique will.

  ## Technique #2: Blend Modes

  This is by far the most versatile technique. It gives you the best control of each layer in your composition.

  <img class="size100" alt="photoshop-double-exposure-technique-3" src="/images/photoshop-double-exposure/photoshop-double-exposure-technique-3.jpg">

  Drag your landscape photo into the portrait from Finder, or use <span class="command">File > Place Embedded...</span>. Either way, make sure you landscape is a Smart Object before you scale it.

  Create a Black & White Adjustment Layer on top above the landscape in the layer stack. Clip this adjustment layer to the landscape photo.

  Change the blend mode of the landscape to <span class="command">Screen</span>. This will make the light areas tranparent, leaving only darker pixels behind.

  To increase the impact of the effect, you can add a Levels or Curves adjustment layer above everything, then clip it to the landscape layer too.

  To finish this off, you can optionally add a Gradient Map adjustment layer on top of the whole composition to give it a vintage look.

  If there are unwanted landscape elements, add a layer mask to the landscape and brush them out in black with a very large soft brush.

assignment: |
  Apply each of the techniques to the provided photos.
---
Double Exposure Effect in Photoshop
http://bit.ly/2h6tmwu

Add a black and white adjustment layer. Make adjustments.
Bring a scene image into the canvas.
Make another black and white adjustment layer. Clip the adjustment layer to the scene photo. Change its blend mode to screen. The goal is to get the scene solid black and white.

