---
layout: submission
type: assignment
formsum: formative
sortorder: 5.3
appsused: psd
title: "Masking Hair"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=289059&grpid=0&isprv=0&bp=0&ou=314355"
submission: "my-assignment-folder"
links:
video: "https://www.youtube.com/embed/zbLqGf6JCZc?rel=0"
downloads: "https://www.dropbox.com/s/8fzflxubke149eb/photoshop-masking-hair.zip?dl=1"
description: "Before you can correct, you must select. This is a time-tested saying amongst Photoshop pros. Learning to make accurate selections of complex and detailed objects in Photoshop is a life-long learning process. We'll continue that here."
details: | 
  The goal of this assignment is to cut an object or person out of a photograph, despite very fine detail. A clipping path would be unmanageable and painting with the brush tool is plain 'ol ugly.

  <figure>
      <img class="size100" alt="photoshop-masking-hair-before-and-after" src="/images/photoshop-masking-hair/photoshop-masking-hair-before-and-after.jpg">
  <figcaption>
    This image shows just how accurately you can select details like hair in a photo using this technique.
  </figcaption>
  </figure>
  One of the strengths of masking in Photoshop is that you can use the characteristics of the image to create a mask. By delving into the channels, we can use higher-contrast areas to mask even the most whispy hair.

  ### Your Workspace

  For this exercise, it's best to clear the panels and only show the ones we want. To that end, hit <span class="command">Shift-Tab</span>. All panels disappear except for the Options bar and tools. Now go to the Window menu, then select the Layers and Channels only.

  Now go <span class="command">Window > Workspace</span> to save the workspace. Name it Masking. Now every time you wish to do this type of work, simply select this workspace.

  <div class="attentionbox tip">
    This is where keyboard shortcuts come in handy. If you know your Zoom shortcuts, you can zoom in and out to check your work, while in a modal dialog. Hint: ⌘-space is your friend.
  </div>

  <figure>
      <img class="size50" alt="photoshop-masking-hairphotoshop-brush-hud" src="/images/photoshop-masking-hair/photoshop-masking-hairphotoshop-brush-hud.jpg">
  <figcaption>
    If you hold Control-Option as you hold down the Brush Tool, you'll get this handy heads up display of your brush tip.
  </figcaption>
  </figure>

  ### Manual Vs. One-Click Methods.

  Considering that Adobe is automating many of these challenging tasks, we always want to compare what we can do manually versus what Photoshop can do automatically. We want to gauge whether it's still worth going the long way, or just clicking a button in Photoshop.

    <figure>
    <img class="size100 borderlightgrey1" alt="photoshop-masking-hair-manual-vs-one-click" src="/images/photoshop-masking-hair/photoshop-masking-hair-manual-vs-one-click.jpg">
  <figcaption>
    On the left, you see the manual method of masking hair. On the right, I used Photoshop's <em>Remove Background</em> function.
  </figcaption>
  </figure>

  The above image proves that the automated method still has a way to go before it reaches the quality of a manual selection.

  ### Layers

  An Alpha Channel in Photoshop is a saved selection represented as a greyscale image. In the panel below, what's white on the channel is selected. What's black is deselected. What's grey is a partial selection -- kind of like onion paper. The lighter the colour on the channel, the more it's selected.

  <figure>
      <img class="size33" alt="photoshop-masking-hair-channels-panel" src="/images/photoshop-masking-hair/photoshop-masking-hair-channels-panel.jpg">
  <figcaption>
    The Channels panel has stored selections called Alpha Channels.
  </figcaption>
  </figure>
  The best way to start is to leverage the present content of the photo. We need to increase the contrast of the photo until we end up with the subject in solid white and the background in solid black (or vice-versa). The black and white version will be loaded as a selection which will be used in a mask.

  Throughout this process, we'll pay special attention to never touch the original layer.

  The first step in the process is the simplest way to increase contrast. Simply duplicate the background layer with <span class="command">Option-⌘-J</span>. Name it *High Contrast*. On the new Layer, go <span class="command">⌘-L</span> or <span class="command">Image >Adjustments >Levels</span>.

  <figure>
      <img class="size100" alt="photoshop-masking-hair-levels-dialogue" src="/images/photoshop-masking-hair/photoshop-masking-hair-levels-dialogue.jpg">
  <figcaption>
    We create a high-contrast version of the photo to separate the subject from the background.
  </figcaption>
  </figure>

  Move the Black Point + White Point sliders inward until the subject gets darker. Stop before the background gets dark. We're just trying to punch-up the subject a little. Click <span class="command">OK</span>.

  <img class="size75" alt="photoshop-masking-hair-step-one-contrast" src="/images/photoshop-masking-hair/photoshop-masking-hair-step-one-contrast.jpg">

  The result we want is getting the background as white as possible and her as dark as possible without losing any of the whispy hairs. Note that you can zoom while the Levels dialogue is open.

  ### Channels

  The Channels panel is where most of the magic happens. While still on our new darker layer, go to the Channels panel. Find the channel where the subject has most contrast with the background. The edges are what counts.

  Duplicate that channel with a right-click. We're going to kind of ruin this channel in the process, so let's call it Damaged.

  Once on this channel, we need to run Levels with <span class="command">⌘-L</span>. In this case, we want to be way more extreme. Bring the black + white point sliders in until we get the subject as black as possible.

  <img class="size75" alt="photoshop-masking-hair-channel-levels" src="/images/photoshop-masking-hair/photoshop-masking-hair-channel-levels.jpg">

  We want to stop with the Levels adjustments before we start to loose detail in the whispy hair, so zoom in to check before you accept.

  Now we have a subject which is almost completely black. Some highlights probably still remain. We need to get rid of them. I simply use a big brush and paint with pure black. Make sure you stop before you paint over the whispy edges of the subject. Just fill in the center with black.

  <img class="size75" alt="photoshop-masking-hair-channel-painted" src="/images/photoshop-masking-hair/photoshop-masking-hair-channel-painted.jpg">

  Use a soft-edged brush. Just be carefull when you get close to the edges. You don't want to paint any black on the white background.

  ### Wrap-up

  By now, you should have a completely black subject, except for the areas where you can see through the hair.

  Now we can go <span class="command">Select > Load Selection</span>. From the dialogue, choose your new channel's name. Click <span class="command">OK</span>. You should see marching ants on your canvas.

  1. Go back to the layers panel.
  2. Turn off the visibility of the Damaged layer.
  3. Double-click on the Background Layer.
  4. Name it something meaningful. Click <span class="command">OK</span>.
  5. Add a mask on this layer by clicking on the <span class="command">Add Layer Mask</span> button at the bottom of the Layers panel.
  6. Voila!

  With a contrasting layer behind your newly-masked subject, you may notice that there are some areas of the photo that are transparent and shouldn't be. Simply go to the mask and paint them white.

  You also have the option of running a Levels command on the mask. This can fine-tune it. But be subtle at this point.

  You're done!

  <img class="size75" alt="photoshop-masking-hair-completed" src="/images/photoshop-masking-hair/photoshop-masking-hair-completed.jpg">

assignment: |
  Mask the main subject in each of the provided images as accurately as you can.

  <div class="attentionbox achtung">
    Make sure to name all of your layers.
  </div>

  ### The Process

  1. Duplicate main layer
  2. Run Levels
  3. Duplicate contrast channel
  4. Run Levels
  5. Paint black (or white)
  6. Load selection
  7. Create layer mask
  8. Optionally run Levels

  <figure>
      <img class="size100" alt="photoshop-masking-hair-completed" src="/images/photoshop-masking-hair/photoshop-masking-hair-exercise-completed.jpg">
  <figcaption>
    This shows my three attempts at masking the subjects in these photos.
  </figcaption>
  </figure>

  For each image, create a new solid background layer. Choose a colour that works. Often, a dark colour brings out a halo effect in the hair of our subjects. This masking process does have its limits.

---
