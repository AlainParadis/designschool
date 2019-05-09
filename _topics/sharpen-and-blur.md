---
layout: default-nav
type: card
formsum: formative
sortorder: 3.4
appsused: psd
title: "Sharpen & Blur"
level: cg4
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=123822&grpid=0&isprv=&bp=0&ou=145538"
submission: "psd-files-in-folder"
links:
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLCUswI9YXYxaFu9nKSO0a1o"
downloads: "https://www.dropbox.com/s/jyl8bb0eh0ewxks/photoshop-sharpen-and-blur.zip?dl=1"
description: "Photoshop doesn't really understand blurry or sharp. It just sees more or less contrast between pixels. It uses different algorithms in its blurring and sharpening tools to achieve its ends. Yeah. Algorithms."
details: |
  ## Sharpening

  ### Smart Sharpen

  The Smart Sharpen filter is a bit more intuitive than the Unsharp Mask filter. There are controls for highlights and shadow areas which give you more control.

  <img class="size100" alt="sharpen-smart-sharpen" src="/images/photoshop-sharpen-and-blur/sharpen-smart-sharpen.jpg">

  <a href="https://helpx.adobe.com/photoshop/how-to/new-smart-sharpen-photoshop.html" target="_blank" title="Adobe's video tutorial on the Smart Sharpen filter.">Video tutorial</a> on the Smart Sharpen filter.

  This is what <a href="https://helpx.adobe.com/photoshop/using/adjusting-image-sharpness-blur.html" target="_blank" title="Adobe's support page for Smart Sharpen">Adobe</a> has to say about the its settings:

  Amount
  : Sets the amount of sharpening. A higher value increases the contrast between edge pixels, giving the appearance of greater sharpness.

  Radius
  : Determines the number of pixels surrounding the edge pixels affected by the sharpening. The greater the radius value, the wider the edge effects and the more obvious the sharpening.

  Reduce Noise
  : Reduce unwanted noise while keeping important edges unaffected.
  
  Remove
  : Sets the sharpening algorithm used to sharpen the image.

    * Gaussian Blur: is the method used by the Unsharp Mask filter.
    * Lens Blur: detects the edges and detail in an image, and provides finer sharpening of detail and reduced sharpening halos.
    * Motion Blur: attempts to reduce the effects of blur due to camera or subject movement. Set the Angle control if you choose Motion Blur.
  
  Angle
  : Sets the direction of motion for the Motion Blur option of the Remove control.

  ### Sharpen with High Pass

  This is a time-tested process for applying a non-destructive sharpening effect to a photo. It can also be applied to a selected area of a photo with the help of a mask.

  <img class="size100" alt="sharpen-high-pass-example" src="/images/photoshop-sharpen-and-blur/sharpen-high-pass-example.jpg">

  Duplicate the photo's layer. Make the new layer a Smart Object. Run <span class="command">Filter > Other > High Pass...</span> on the Smart Object. Dial up the settings until you start to see colour through the grey. Back it off only until the colour is gone.

  Click <span class="command">OK</span>. Change the blend mode of the Smart Object to <span class="command">Overlay</span>. Since you made the layer a Smart Object, you can double-click on the High Pass entry in your Layers panel to edit the High Pass settings after the fact.

  ### Unsharp Mask

  The Unsharp Mask filter increases contrast between neighbouring pixels. The radius setting determines the size of the area inside which the pixels will be compared. The Threshold settings determines how different the pixels need to be before they are affected by the filter. So, Threshold has a mitigating effect.

  <img class="size100" alt="sharpen-unsharp-mask" src="/images/photoshop-sharpen-and-blur/sharpen-unsharp-mask.jpg">

  Only use this filter on a Smart Object or on a duplicate of your layer. A Smart Object is better.

  ### Shake Reduction

  Bluriness can be caused by either your camera or your subject moving as you take your photo. The result is a motion blur of your subject.

  <img class="size100" alt="sharpen-shake-reduction" src="/images/photoshop-sharpen-and-blur/sharpen-shake-reduction.jpg">

  As usual, it's best to convert to your layer to a Smart Object. Go <span class="command">Filter > Sharpen > Shake Reduction...</span>. This is what <a href="https://helpx.adobe.com/photoshop/using/reduce-camera-shake-induced-blurring.html" target="_blank" title="Adobe's support page about the Shake Reduction filter.">Adobe</a> has to say about the filter.

  Blur Trace Bounds: The Blur Trace Bounds setting represents the bound size of the blur trace. You can adjust this value if necessary.

  Source Noise: Photoshop automatically estimates the amount of noise in the image. If necessary, select a different value (Auto/Low/Medium/High).

  Smoothing: Smoothing reduces high-frequency sharpening noise. You can move the slider to a value different from the default 30%. A low Smoothing setting is recommended.

  Artifact Suppression: Sometimes, in the course of sharpening the image, you may observe some noticeable noise artifacts.

  ## Blurs

  More often than not, we want to sharpen a blurry photo. But sometimes, intentionally blurring a photo can add drama, motion or a short depth of field to your composition. We'll explore all these effects and more in this exercise. There are a range of blurring tools available in Photoshop. The first we'll look at is the Blur Gallery.

  ### Blur Gallery

  <img class="size50" alt="blur-menu" src="/images/photoshop-sharpen-and-blur/blur-menu.jpg">

  Before we apply any filters in Photoshop, we always want to ensure we're working on a Smart Object. This will make it that the filters are non-desctructive. That means that the actual pixel data of the photo will not be touched. The filters on a Smart Object are kind of on their own layer, separate from the photo's pixels.

  <img class="size50" alt="blurs-convert-to-smart-object" src="/images/photoshop-sharpen-and-blur/blurs-convert-to-smart-object.jpg">

  ### Control UI

  When you envoke the blurs from the Blur Gallery, you can control them either from the on-screen controls or from the Control Bar along the top of the screen. These are the on-screen controls.

  <img class="size75" alt="blur-ui" src="/images/photoshop-sharpen-and-blur/blur-ui.jpg">

  ### Field Blur

  It's only logical that the photo is in a field, right?

  The blur effect is linear. <a href="https://helpx.adobe.com/photoshop/using/blur-gallery.html" target="_blank" title="Adobe's support page about Blur Gallery" class="sans">Adobe</a>: Use Field Blur to build a gradient of blurs, by defining multiple blur points with different amounts of blur. Add multiple pins to the image and specify a blur amount for each pin. The final result is combined effect of all blur pins on the image. You can even add a pin outside the image, to apply the blur at corners.

  Go <span class="command">Filter > Blur Gallery > Field Blur</span>.

  <img class="size75" alt="blurs-field-blur-example" src="/images/photoshop-sharpen-and-blur/blurs-field-blur-example.jpg">

  In the Control bar, you can opt to save the mask to your Channels panel, in case you wish to apply the mask to something else in your composition.

  ### Iris Blur

  It's only logical that the photo has an iris in it, right?

  <img class="size75" alt="blurs-iris-blur-example" src="/images/photoshop-sharpen-and-blur/blurs-iris-blur-example.jpg">

  The blur effect is radial. <a href="https://helpx.adobe.com/photoshop/using/blur-gallery.html" target="_blank" title="Adobe's support page about Blur Gallery" class="sans">Adobe</a>: Use the Iris blur to simulate a shallow depth-of-field effect to your picture, irrespective of the camera or lens used. You can also define multiple focus points, an effect almost impossible to achieve using traditional camera techniques.

  ### Spin Blur

  <img class="size75" alt="blurs-spin-blur-example" src="/images/photoshop-sharpen-and-blur/blurs-spin-blur-example.jpg">

  The blur effect is radial. <a href="https://helpx.adobe.com/photoshop/using/blur-gallery.html" target="_blank" title="Adobe's support page about Blur Gallery" class="sans">Adobe</a>: Using the Spin Blur effect, you can rotate and blur the image around one or more points. The spin blur is a radial blur measured in degrees. Photoshop lets you work with center points, blur size and shape, and other settings, all while viewing a live preview of the changes.

  ### Tilt Shift Blur

  <img class="size75" alt="blurs-tilt-shift-example" src="/images/photoshop-sharpen-and-blur/blurs-tilt-shift-example.jpg">

  The blur effect is radial. <a href="https://helpx.adobe.com/photoshop/using/blur-gallery.html" target="_blank" title="Adobe's support page about Blur Gallery" class="sans">Adobe</a>: Use the <a href="https://en.wikipedia.org/wiki/Tilt&ndash;shift_photography" target="_blank" title="Wikipedia's page on Tilt-Shift photography.">Tilt-Shift effect</a> to simulate an image taken with a tilt-shift lens. This special effect blur defines area of sharpness, and then fades to a blur at the edges. The Tilt-Shift effect can be used to simulate photos of miniature objects.

assignment: |
  Sharpen the provided images with the techniques listed below. Be sure you <span class="command">Convert for Smart Filters</span> at the outset.

  #### Smart Sharpen

  <img class="size100" alt="exercise-sharpen-smart-sharpen" src="/images/photoshop-sharpen-and-blur/exercise-sharpen-smart-sharpen.jpg">


  #### Sharpen with High Pass

  <img class="size100" alt="exercise-sharpen-smart-sharpen" src="/images/photoshop-sharpen-and-blur/exercise-sharpen-high-pass.jpg">

  #### Unsharp Mask

  <img class="size100" alt="exercise-sharpen-unsharp-mask" src="/images/photoshop-sharpen-and-blur/exercise-sharpen-unsharp-mask.jpg">

  #### Shake Reduction

  <img class="size100" alt="exercise-sharpen-shake-reduction" src="/images/photoshop-sharpen-and-blur/exercise-sharpen-shake-reduction.jpg">

  ### Blurs

  Apply blurs from the Blur Gallery as shown below. Be sure you <span class="command">Convert for Smart Filters</span> at the outset.

  #### Field Blur

  <img class="size100" alt="exercise-blur-field-blur" src="/images/photoshop-sharpen-and-blur/exercise-blur-field-blur.jpg">

  #### Iris Blur

  <img class="size100" alt="exercise-blur-iris-blur" src="/images/photoshop-sharpen-and-blur/exercise-blur-iris-blur.jpg">


  #### Spin Blur

  <img class="size100" alt="exercise-blur-spin-blur" src="/images/photoshop-sharpen-and-blur/exercise-blur-spin-blur.jpg">

  Once you've used the Spin Blur filter, you'll need to paint out regions on the filter's mask. You want to make sure you don't blur the fender or the ground.

  #### Tilt Shift Blur

  <img class="size100" alt="exercise-blur-tilt-shift-1" src="/images/photoshop-sharpen-and-blur/exercise-blur-tilt-shift-1.jpg">

  <img class="size100" alt="exercise-blur-tilt-shift-2" src="/images/photoshop-sharpen-and-blur/exercise-blur-tilt-shift-2.jpg">

---
https://helpx.adobe.com/photoshop/using/blur-gallery.html

https://helpx.adobe.com/photoshop/key-concepts/blur.html

https://helpx.adobe.com/photoshop/how-to/add-motion-blur-effects.html

https://helpx.adobe.com/photoshop/using/adjusting-image-sharpness-blur.html

  Put this in CG4, also.

  ## <a href="https://helpx.adobe.com/photoshop/using/adjusting-image-sharpness-blur.html" target="_blank">Useful link</a>

  Anti-Aliasing: <a href="https://helpx.adobe.com/photoshop/key-concepts/aliasing-anti-aliasing.html" target="_blank" title="">Add content from this page</a>.

  Regular Blur filters: <a href="https://helpx.adobe.com/photoshop/using/filter-effects-reference.html#blur_filters" target="_blank" title="Submit your assignment on Brightspace.">Info here</a>.
