---
layout: submission
type: assignment
formsum: formative
sortorder: 3.1
appsused: psd
title: "Colour Correction"
level: cg4
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=384446&grpid=0&isprv=0&bp=0&ou=411216"
submission: "my-assignment-folder"
links: 
downloads: "https://www.dropbox.com/s/mhf0ay8it0kwvnx/photoshop-colour-correction.zip?dl=1"
description: "We'll explore techniques which take the guesswork out of making colour corrections in Photoshop."
details: |
  If you ask a thousand designers for their colour correction techniques, you'd likely get a thousand different techniques. A large majority of them involve a lot of guesswork and subjective adjustments.

  ### The Fab Five

  The five properties to address in colour correction:

  * Tonal range: Adjust the lightest and darkest areas of the photo.
  * Colour casts: Adjust mid tones to ensure they are indeed neutral (no colour casts).
  * Contrast: Optimize contrast in key areas of the photo.
  * Blur: Apply sharpening as needed.
  * Sharpen: Sharpen non-destructively

  ### Levels

  <img class="size50" alt="photoshop-colour-correction-levels-dialogue" src="/images/photoshop-colour-correction/colour-correction-levels-dialogue.jpg">

  Moving the White Point or Black Point to the centre increases the contrast. Moving the mid point re-maps the mid tones of the image.

  The Output levels are not used in colour correction, but they can be used to compensate for the lack of tonal range in a specific output device.

  Ensure that you do not make too drastic changes within the Levels dialogue. This can cause banding (posterization).

  The Eye Dropper tools within the Levels dialogue is used to set the light, mid and black points in the image. Simply select one of the tools and click in the corresponding area of the image.

  As an option to using Threshold, holding ALT/OPTION after selecting the White/Black point adjustment tool will toggle Clipping preview and the Red pixels are the ones to target.

  ### Set White Point

  In the image below, you can see that whites are not actually white. That's what we need to correct. You don't need to guess at this. You can see the span indicated in the histogram that there's a whole range of white missing from the photo.

  <img alt="photoshop-colour-correction-set-white-point-histogram" src="/images/photoshop-colour-correction/colour-correction-set-white-point-histogram.jpg">

  The first step is to find the current whitest pixel. Use a Threshold Adjustment Layer. Move the slider from the right towards the left until a white pixel apears on the screen. You should zoom in to find the actual whitest pixel.

  <img class="size75" alt="photoshop-colour-correction-set-white-point-threshold" src="/images/photoshop-colour-correction/colour-correction-set-white-point-threshold.jpg">

  The numbers for the marker we put down should be 255, which would indicate a totally white white. White is 255 of 255. Black is 0/255.

  Now that we have identified the current lightest pixel (white isn't actually white) we'll use a Levels Adjustment Layer to make it actually white (255 of 255) without guess-work.

  <img class="size75" alt="photoshop-colour-correction-levels-set-white-point" src="/images/photoshop-colour-correction/colour-correction-levels-set-white-point.jpg">

  <img class="size75" alt="photoshop-colour-correction-white-point-before-after" src="/images/photoshop-colour-correction/colour-correction-white-point-before-after.jpg">

  ### Set Black Point

  When you find a *washed out* photo, it often means that blacks are not actually black. We'll find the current darkest pixel in the photo. We'll make it black, which will pull all the other pixels in a darker direction.

  In the image below, you can see that the histogram is shifted way over to the right. That means that the darkest colours in the photo are nowhere near black. We need to correct that.

  <img class="size75" alt="colour-correction-white-point-histogram" src="/images/photoshop-colour-correction/colour-correction-white-point-histogram.jpg">

  Before we can set a new black point, we need to find the current darkest pixel in our photo. The problem is that this darkest pixel isn't actually black.

  <img class="size75" alt="colour-correction-threshold-black-point" src="/images/photoshop-colour-correction/colour-correction-threshold-black-point.jpg">

  The first step is to find the darkest pixel in the image. We use a Threshold Adjustment Layer to do so. Add a Threshold Adjustment Layer. To find the black point, move the slider all the way to the left, then gradually move it towards the right, until a black pixel appears on the screen. You may need to zoom in to see the very first pixel.

  Mark that pixel with the Eye Dropper tool by shift-clicking on it. This will leave a marker, as shown above.

  <img class="size75" alt="colour-correction-set-black-point" src="/images/photoshop-colour-correction/colour-correction-set-black-point.jpg">

  Now, we're ready to set the black point. We can hide the visibility of the Threshold layer. Add a Levels Adjustment Layer. Use its Black Point tool to click on the marker you placed on the image. This will shift the histogram as shown above.

  The pixel we orginally marked was not black. Now it is. You can test this by zooming in on the marker, then sampling it with your Eye Dropper tool.

  <img class="size75" alt="photoshop-colour-correction-black-point-before-after" src="/images/photoshop-colour-correction/colour-correction-black-point-before-after.jpg">

  ### Remove a Colour Cast

  A photo taken in an brightly coloured environment can often cause a colour cast on the subject. We want to neutralize this effect. The first step is to determine what colour the cast is. For this, we'll use a cool little layers trick.

  <img class="size75" alt="colour-correction-fill-50pc-grey" src="/images/photoshop-colour-correction/colour-correction-fill-50pc-grey.jpg">

  Start by adding a new empty layer on top of the photo. Fill it with 50% grey. After you've filled the layer, switch the blend mode  to <span class="command">Difference</span> in the Layers panel.

  <img class="size75" alt="colour-correction-fill-threshold" src="/images/photoshop-colour-correction/colour-correction-fill-threshold.jpg">

  Now on a new Threshold Adjustment Layer, drag the slider from left to right until a black pixel appears. Mark it with a Shift-click of the Eye Dropper tool.

  <img class="size75" alt="colour-correction-levels-mid-point" src="/images/photoshop-colour-correction/colour-correction-levels-mid-point.jpg">

  Add a Levels Adjustment Layer, then use the mid-point eye dropper to click on your marker. You can clearly see that the pixels in the area are not a neutral grey, but rather greener.

  <img alt="colour-correction-cast-before-after" src="/images/photoshop-colour-correction/colour-correction-cast-before-after.jpg">

  From close up you'll see a slight shift in colour. Zoom out and flash the Levels layer on and off to see the difference. The key here is that there was no guess-work in the process. It's all done by the numbers. Just follow the steps and you're get the results.

  <img alt="colour-correction-colour-balance-adj-layer" src="/images/photoshop-colour-correction/colour-correction-colour-balance-adj-layer.jpg">

  That said, if you want to make further manual adjustments, you can use a Colour Balance Adjustment Layer. In this case, we know that the photo had a yellow colour cast. We used the Colour Balance Adjustment Layer to slide away from yellow to make the correction.

  ### Do It For Me

  Now that we know how the fundamentals work, let's see if Photoshop can cut to the chase and do all this for us. Introducing the Auto Levels feature.

  To have Photoshop correct your image for you automatically, add a Levels or a Curves adjustment layer. Option-click on the <span class="command">Auto</span> button in the Properties panel.

  <img class="size33" alt="photoshop-auto-levels" src="/images/photoshop-layers/photoshop-auto-levels.jpg">

  Photoshop has algorithms built in to analyse your image and make corrections in four different ways. <a href="https://helpx.adobe.com/photoshop/using/making-quick-tonal-adjustments.html" title="Adobe on Auto Levels" target="_blank">This is what Adobe has to say</a> about the four algorithms:

  <dl>
    <dt>Enhance Monochromatic Contrast:</dt>
      <dd>Clips all channels identically. This preserves the overall color relationship while making highlights appear lighter and shadows appear darker. The Auto Contrast command uses this algorithm.</dd>
    <dt>Enhance Per Channel Contrast:</dt>
      <dd>Maximizes the tonal range in each channel to produce a more dramatic correction. Because each channel is adjusted individually, Enhance Per Channel Contrast may remove or introduce color casts. The Auto Tone command uses this algorithm.</dd>
    <dt>Find Dark & Light Colors:</dt>
      <dd>Finds the average lightest and darkest pixels in an image and uses them to maximize contrast while minimizing clipping. The Auto Color command uses this algorithm.</dd>
    <dt>Snap Neutral Midtones:</dt>
      <dd>Adjusts midtones so that colours that are close to neutral are mapped to the target neutral colour. This can remove a colour cast.</dd>
  </dl>

  When setting White/Black point, or Per Channel Auto a good way to reduce any colour shift is to set the adjustment blend mode to Luminosity. This keeps the Shadow/Highlight correction but ignores the hue shifts.

  ### Sharpening

  As soon as you resize a photo out of your camera or a scan, the re-mapping of the pixels on the canvas will cause blurriness. We want to gently sharpen the photo. If we sharpen too much we'll get a halo effect in high-contrast areas, which we want to avoid.

  #### Sharpen with High Pass

  We'll use Smart Objects with filters to gently sharpen the image in a non-destructive way. Start with duplicating the layer you wish to sharpen.

  <img class="size75" alt="colour-correction-high-pass-filter" src="/images/photoshop-colour-correction/colour-correction-high-pass-filter.jpg">

  The first steps are to duplicate the background layer, then convert it to a Smart Object. Now, go Filter > Other > High Pass... Keep cranking up the value, then back it off before colour starts to show through the grey.

  Set the grey layer to blend mode <span class="command">Overlay</span>. Double-click on the High Pass filter in the Layers panel if you need to edit the results.

  <img class="size50" alt="colour-correction-sharpen-before-after" src="/images/photoshop-colour-correction/colour-correction-sharpen-before-after.jpg">

  ### Sharpening with Unsharp Mask

  When sharpening an image, you should ask a few essential questions:

  What is the purpose of the image? Will it be used in print, on the Web? Will it be archived? Will it only be used once, or over and over again in corporate publications? At what size will this image be reproduced? Should you edit individual channels or the whole image globally?

  #### Sharpen: Unsharp Mask

  The Unsharp Mask filter is our go-to, most versatile sharpening filter. The terminology is a bit un-intuitive, but it really works well. There are no magic numbers for the Unsharp Mask filter. You have to make a decision on the values to enter.

  <div class="attentionbox tip">
    Don't forget to convert the the layer to a Smart Object. Right-click on the layer name, then click on Convert to Smart Object.
  </div>

  <img class="size75" alt="colour-correction-unsharp-mask-test-grey" src="/images/photoshop-colour-correction/colour-correction-unsharp-mask-test-grey.jpg">

  Above is a test image I created to demonstrate how the Unsharp Mask filter works. I've over-sharpened it on purpose. The file is in the downloads folder. It's useful for getting a grasp on what the three Threshold variables do to an image. Play with this to try to wrap your brain around it.

  ##### Amount

  The sharpening illusion depends on a light/dark halo effect. The Amount value determines the intensity of the halo, but not its width. High Amount values cause very high contrast halo effects which are more harmful to the image.

  ##### Radius

  The Radius setting controls the width of the halo. The wider the halo, the more obvious the sharpening effect. Radius is your first setting, because it is most dependant on the content of the photo. You should try to keep this value between 0.5 and 1.5. The less detail in your image, the higher the Radius number can be.

  ##### Threshold

  Threshold acts as a damper to the two other variables in UnSharp Mask. Threshold really says *don't sharpen until there's this much difference between the shapes*. Threshold tells Photoshop how far apart two pixels' tonal values have to be before they are affected by the filter.

  <img alt="colour-correction-unsharp-mask-flower" src="/images/photoshop-colour-correction/colour-correction-unsharp-mask-flower.jpg">

  In the flower image above, the sharpening is quite subtle. You can see the sharper pixels on the yellow stamen of the flower.

  ### Remove Noise

  You'll often get noisy images in low-light high ISO value photos. No matter the cause of the noise, we need a non-destructive method for removing it.

  <div class="attentionbox tip">
    As always, to get the most accurate depiction of your photo on-screen, type cmd-1 to view your image at 100%. That means one image pixel is being depicted with one of your monitor's pixels.
  </div>

  What we have below is a noisy wedding photo. You can see that the left side of her face is fixed. It looks a bit blurry, but I'm zoomed in really close.

  <img alt="colour-correction-reduce-noise-before-after" src="/images/photoshop-colour-correction/colour-correction-reduce-noise-before-after.jpg">

  The simplest way to get rid of noise is to use the Reduce Noise filter on a Smart Object layer. Go <span class="command">Filter > Noise > Reduce Noise...</span>

  <img class="size100" alt="colour-correction-reduce-dialogue" src="/images/photoshop-colour-correction/colour-correction-reduce-dialogue.jpg">

  The Reduce Noise filter has two modes: Basic & Advanced. The basic settings are:

  Strength: This basically blurs your image, so you want to go easy.

  Preserve Details: Looks for detail areas and doesn't reduce the noise as much there.

  Reduce Colour Noise: Colour noise is the red, green and blue pixels you sometimes see when you're zoomed really close into a photo. This reduces that.

  Sharpen Details: This is pretty much the reverse of Preserve Details. It increases the contrast between pixels in detail areas.

  These settings really depend on the amount of detail in your photo. Start by increasing the Strength setting. The danger is that it makes your photo blurry. If it does, adjust the other settings until you're satisfied.

  The true test is to use the photo. If it's meant for print, do a test print. If it's meant for the screen, post it. If it needs further adjustment, go back to your layered Photoshop file and make adjustments.

assignment: |
  Follow the instructions in the provided folder to process each photo.

  ### Manual Colour Correction

  Do these manually. We'll need to see Threshold layers in each of your files marking the black and/or white points. You'll also have a Levels adjustment layer for the actual corrections.

  <img class="size100" alt="formative-assignment-completed" src="/images/photoshop-colour-correction/formative-assignment-manual-completed.jpg">

  ### Auto Colour Correction

  Complete the provided images using the Auto command. In this case, you should finish with only one Adjustment Layer.

  <img class="size100" alt="formative-assignment-auto-completed" src="/images/photoshop-colour-correction/formative-assignment-auto-completed.jpg">

  ### The Sharpening

  Sharpen the provided photos using the High Pass process.
---
