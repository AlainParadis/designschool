---
layout: submission
type: assignment
formsum: formative
sortorder: 5.4
appsused: psd
title: "Retouching Fundamentals"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=354449&grpid=0&isprv=0&bp=0&ou=372612"
submission: "my-assignment-folder"
links: |
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/retouching-repairing-images.html" target="_blank" title="Adobe: Retouch & Repair Photos">Retouch & Repair Photos</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/content-aware-patch-move.html" title="Adobe: Content-Aware Patch and Move" target="_blank">Content-Aware Patch and Move</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLDkwOG1w_wxTWQLU3tf88Bi"
downloads: "https://www.dropbox.com/s/o068h1i5uku7102/photoshop-retouching-fundamentals.zip?dl=1"
description: "We'll use the Clone Stamp Tool, the Healing Brush and Content Aware tools to remove blemishes from a photograph."
details: |
  Whether they're blemishes on skin or stains on a surface, Photoshop has a tool to remove them quite easily. Our focus here will be on working non-destructively. That means that we don't want to paint on the original photo at all. The added advantage working this way is that our painting will be accessible on their own layers.

  <figure>
    <img class="size75" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icons-psd-cloning.svg">
  <figcaption>
  <ol>
  <li>Clone Stamp Tool</li>
  <li>Spot Healing Brush Tool</li>
  <li>Healing Brush Tool</li>
  <li>Patch Tool</li>
  <li>Red Eye Tool</li>
  </ol>
  </figcaption>
  </figure>

  These are the tools we'll focus on. They're all made to repair photographs.
  ### Clone Stamp Tool

  <img class="size15" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icon-clone-stamp.svg">

  The Clone Stamp Tool is often called the rubber stamp tool for a reason. It works very similarly. You take a sample on your photo, then you replicate it at another location. The goal is most often to cover up something under the cloning.

  <img alt="retouching-clone-stamp-tool" src="/images/photoshop-retouching-fundamentals/retouching-clone-stamp-tool.jpg" class="size100">

  <div class="attentionbox tip">
    Create a new empty layer called Cloning. Do not duplicate the photo's layer.
  </div>

  The Clone Stamp Tool doesn't do any calculations or adjustments. It just clones the pixels you sampled, no matter whether they match or not.

  ### Healing Brush

  <img class="size15" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icon-spot-healing-brush.svg">

  The Healing Brush Tool works very similarly to the Clone Stamp Tool, except that it's a smarter tool. You need to sample an area first. When you release the mouse while cloning, it evaluates the surrounding pixels then adjusts the cloned pixels to blend into their surroundings.

  ### Spot Healing Brush Tool

  <img class="size15" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icon-healing-brush.svg">

  The Spot Healing Brush works by simply clicking on blemishes. There's no need to sample pixels first. Just adjust the diameter and hardness of your brush, then click away. Just make sure you're on a new, empty layer.

  This is the perfect tool for removing blemishes on a subject's skin. It should be your go-to tool. If you find it not bending to your will, go back to the Clone Stamp Tool.

  ### Patch Tool

  <img class="size15" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icon-patch-tool.svg">

  The Patch Tool is made to fix blemishes on large, rather flat surfaces in a photo. The idea is that you drag a good part of the photo on top of a damaged part of the photo. The tool does the work of blending the patch into its surroundings.

  <figure>
      <img class="size100" alt="retouching-scar-patch" src="/images/photoshop-retouching-fundamentals/retouching-scar-patch.jpg">
  <figcaption>
    The scar was repaired using the Patch tool on Content Aware mode on its own layer.
  </figcaption>
  </figure>

  Note that if the Patch setting is at Normal, the tool doesn't work on a separate layer. It's best to set it to Content Aware, then work on a new empty layer named Patching.

  ### Patch Settings

  <dl>
    <dt>Structure</dt>
      <dd>Enter a value between 1 and 7 to specify how closely the patch should reflect existing image patterns. If you enter 7, the patch adheres very strongly to existing image patterns. If you enter 1, the patch adheres very loosely to the existing image patterns.</dd>
    <dt>Color</dt>
      <dd>Enter a value between 0 and 10 to specify the extent to which you want Photoshop to apply algorithmic color-blending to the patch. If you enter 0, color blending is disabled. A Color value of 10 applies maximum color blending.</dd>
    <dt>Sample All Layers</dt>
      <dd>Enable this option to create the result of the move in another layer using information from all layers. Select the target layer in the Layers panel.</dd>
  </dl>

  ### Red Eye Tool

  <img class="size15" alt="Photoshop's Retouching Tools" src="/images/photoshop-retouching-fundamentals/tool-icon-red-eye.svg">

  <span class="orange fw500">Let's avoid using this tool.</span> We'll use a Hue/Saturation adjustment layer instead.

  We've all seen the red eye effect in photos. Few know that it comes from light from your flash bouncing off the blood vessels at the back of the eye to return to your camera.

    <figure>
    <img class="size100 borderdarkgrey1" alt="repairing-blemishes-removing-red-eye" src="/images/photoshop-retouching-fundamentals/repairing-blemishes-removing-red-eye.jpg">
  <figcaption>
    Use an Adjustmet Layer to desaturate the red from the eyes. This preserves the detail in the pupils.
  </figcaption>
  </figure>


  Create a Hue/Saturation Adjustment Layer. Turn the Saturation down to -100. Invert your mask to make it black. Then pain the red eyes with a very soft white brush.

  > A reflection of the camera flash in the subject’s retina causes red eye. You’ll see it more often when taking pictures in a darkened room because the subject’s iris is wide open. To avoid red eye, use the camera’s red eye reduction feature. Or, better yet, use a separate flash unit that you can mount on the camera farther away from the camera’s lens.
  <cite><a href="https://helpx.adobe.com/photoshop/using/retouching-repairing-images.html" title="Adobe's notes on the Red Eye Tool." target="_blank">From: Adobe</a></cite>

  ### Skin Smoothing

  We'll explore the best process for smoothing skin. It's documented in the video tutorial in the playlist above. These are the steps:

  Before we start, we'll make a new composite layer by targeting all the layers, then holding Option while going to <span class="command">Layers > Merge Visible</span>.

  1. Duplicate the subject's layer
  1. Convert it to a Smart Object
  1. Go Filter > Other > High Pass, 24
  1. Go Filter > Blur > Gaussian blur, 8
  1. ⌘-I to invert
  1. Set Bend Mode to Linear Light
  1. Set Blending options
  1. Mask out unwanted areas

  ### The Final Product

  The important factor is to never touch the original photo. Make sure edits you make are on their own layers. This allows you to return to the photo to make changes. You can also turn off your new layers to see the original photo.

  <figure>
      <img class="size100" alt="retouching-before-after" src="/images/photoshop-retouching-fundamentals/retouching-before-after.jpg">
  <figcaption>This shows the final retouched photo. Note that all the edits are on separate layers.
  </figcaption>
  </figure>

  ### Content Aware Tools

  The Content Aware Tools in Photoshop are truly magical. They make a really good guess at how you want to fill in shapes. All you do is lasso the unwanted area, then <span class="command">Edit > Fill > Content Aware Fill</span>. Presto!

  <figure>
      <img class="size100" alt="content-aware-fill" src="/images/photoshop-retouching-fundamentals/content-aware-fill.jpg">
  <figcaption>
    Make a selection, then use the Fill command with Content Aware. Sometimes it needs to be done in sections.
  </figcaption>
  </figure>
  Go ahead and try. Lasso the lamp, then go <span class="command">Edit > Fill > Content Aware...</span> When the surfaces differ a lot, it's better to do it in multiple steps.

  <div class="attentionbox tip">
  If you're zoomed in really closely, you can hold h, then click-hold with your mouse to zoom out and choose another zoom location. Go ahead; give it a whirl.
  </div>
assignment: |
  Fix blemishes on the provided photo with any of the tools above, as needed. Feel free to use an <a href="adjustment-layers.html" target="_blank" title="a"><a href="adjustment-layers.html" title="adjustment layer">adjustment layer</a></a>. You'll likely need them to colour her lips and maybe her eyes. You can run the skin smoothing technique. Gently.
  
  <img class="size100" alt="photoshop-retouching-fundamentals-exercise" src="/images/photoshop-retouching-fundamentals/photoshop-retouching-fundamentals-exercise.jpg">
  
  It's very important that your work is non-destructive. The focus of this assignment is has two goals:
  
  1. repair blemishes seamlessly.
  2. make repairs non-destructive -- do not touch the original photo.

   You can create layers as needed. I usually create a layer for each separate task. Remember to name all of your layers with a meaningful name.

  ### Blemishes & Teeth Whitening

  All you need to do in this photo is remove the blemishes, then whiten the man's teeth using the technique we practiced in class. Make sure it doesn't look over-done.

  <img class="size100 borderdarkgrey1" alt="summative-teeth-whitening" src="/images/photoshop-retouching-fundamentals/summative-teeth-whitening.jpg">
  
  Do not use the skin smoothing on this photo.

  ### Content Aware Fill

  Use Content Aware Fill to remove the microphone and light from the background.

  <img class="size100" alt="summative-content-aware-fill" src="/images/photoshop-retouching-fundamentals/summative-content-aware-fill.jpg">

  Save, then close the document.
---
