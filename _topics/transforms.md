---
layout: submission
type: assignment
formsum: formative
sortorder: 3.2
appsused: psd
title: "Transforms"
level: cg4
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=123821&grpid=0&isprv=&bp=0&ou=145538"
submission: "my-assignment-folder"
links: |
  - <a href="https://helpx.adobe.com/photoshop/using/transforming-objects.html" target="_blank" title="Transform Objects">Transform Objects</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLCPV88lerrXcuLpXw0bX4q-"
downloads: "https://www.dropbox.com/s/ho5atnoj3grivpp/photoshop-transforms.zip?dl=1"
description: "In this lesson, we'll explore the limitless transformation capabilities of Adobe Photoshop; all in a non-destructive workflow, of course."
details: | 
  ## Basic Transforms

  Before we apply transformations to a layer in Photoshop, we want to ensure our editing is non-destructive. To that end, convert your layer to a Smart Object by right-clicking on the canvas with the Marquee tool, then choosing <span class="command">Convert to Smart Object</span>. Now, however you transform your layer, you can edit the settings.

  You can use the various tranform tools under <span class="command">Edit > Transform...</span>. The first five types of transforms are similar. <span class="command">Warp</span> is in a category of its own, so it gets a different Control bar. For the most part, the transforms keep the edges of your image straight. The <span class="command">Warp</span> transformations curve the edges based on the selected envelope. Envelopes are different warp transformation shapes.

  <img class="size50" alt="photoshop-transforms-menu" src="/images/photoshop-transforms/photoshop-transforms-menu.jpg">

  While you have an active transform bounding box, the Control bar along the top of the screen gives you transformation options.

  <img alt="photoshop-transforms-control-bar" src="/images/photoshop-transforms/photoshop-transforms-control-bar.jpg">

  The button indicated above switches the transform bounding box between Transform mode and Warp mode. You can switch between both modes with the button. You can also do multiple tranforms in one operation by switching modes and switching warp envelopes. Once you're done, simply click the check box in the Control bar.

  <div class="attentionbox tip">
    My favourite way of accessing all these tranform functions is with the ⌘-T keyboard shortcut. Once the transform bounding box is active, right-click on the canvas to select a transform mode.
  </div>

  <img class="size50" alt="photoshop-transforms-practice" src="/images/photoshop-transforms/photoshop-transforms-practice.jpg">

  Let's open the practice file to work with the various transform commands. We'll perform transforms to have the green squares match the grey ones. Some key maneuvers include holding <span class="command">Shift</span> and/or <span class="command">Option</span>.

  <img class="size100" alt="photoshop-warp-bottle-before-after" src="/images/photoshop-transforms/photoshop-warp-bottle-before-after.jpg">

  We'll use the Warp transformation tool to fit the label to the bottle. This workflow will also include Blend Modes, Clipping Masks, Adjustment Layers and Smart Objects.

  ## Vanishing Point

  Vanishing point is a great way to introduce one image into another and match the perspective. We'll place the image of the lizzard below on the wall of the building.

  <img class="size75" alt="photoshop-transforms-vanishing-point-example" src="/images/photoshop-transforms/photoshop-transforms-vanishing-point-example.jpg">

  Open both photos. In the lizzard image, select all (⌘-A) and copy (⌘-C). In the building image, create a new empty layer. Now we're ready to enter the filter. Go <span class="command">Filter > Vanishing Point...</span>.

  <img class="size75" alt="photoshop-transforms-vanishing-point-draw-mesh" src="/images/photoshop-transforms/photoshop-transforms-vanishing-point-draw-mesh.jpg">

  Use the Create Plane tool to draw planes on each surface of the building. The plane grids which are red don't line up with the vanishing points. Make sure yours are blue.

  You can change surfaces by ⌘-dragging the Create Plane tool. Once you have your planes in place, simply paste the lizzard into the dialogue. You can scale and move it with the Transform tool. Once the lizzard looks right, click <span class="command">OK</span>.

  The final step is to change the blend mode of the Lizzard layer to <span class="command">Multiply</span>. If you want to place another lizzard, it's best to repeat the whole process on a new layer.

  ## Puppet Warp

  Puppet Warp bends shapes naturally. The function is available under <span class="command">Edit > Puppet Warp</span>. It's best to isolate the object on its own layer.

  It's very useful for shaping humans as an alternative to the Liquify command. You can can pull in bulges, create a smile or <a href="http://i1.ytimg.com/vi/1qenoB_1kO4/maxresdefault.jpg" target="_blank" title="Use Puppet Warp to re-shape humans.">move a limb into position</a>.

  <img class="size100" alt="photoshop-transforms-puppet-warp-example" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-example.jpg">

  As always, before we use the Puppet Warp tool we want to convert our layer to a Smart Object to preserve editability.

  Choose <span class="command">Edit > Puppet Warp...</span> There are important settings in the Control bar. You can show/hide the mesh. You can also edit the density of the mesh to increase or decrease control points.

  <img class="size75" alt="photoshop-transforms-puppet-warp-controls" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-controls.jpg">

  You need to click on the object to put down pins. The pins hold that area in place as an actual thumb tack would. Click and drag a pin to warp the object. The pins anchor parts of the warped object in place. You can hold the Shift key to select more than one at a time to move more of the object at once. To remove a pin, you can Option-click on one.

  To rotate around a pin, hole the Option key, then hover your mouse near a pin. A circle will appear allowing you to rotate the object around the pin.

  Once you have the look you want, click on the check mark in the Control bar, or hit <span class="command">Enter</span>.

  <img class="size33" alt="photoshop-transforms-puppet-warp-modes" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-modes.jpg">

  There are three warp modes:

  Normal: Is normal.

  Rigid: Keeps the object stiffer as it bends.

  Distort: Distorts more freely. There's more scaling going on.

  <img class="size75" alt="photoshop-transforms-puppet-warp-stacking" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-stacking.jpg">

  If you twist your object so it overlaps itself, you can set the stacking order so it either goes behind or in front of itself as it twists.

  <img class="size75" alt="photoshop-transforms-puppet-warp-reset" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-reset.jpg">

  If things get too messed up, you can click the reset button in the Control bar.

  <img class="size100" alt="photoshop-transforms-puppet-warp-before-after" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-before-after.jpg">

  ## Perspective Warp

  Photoshop has a really handy feature that allows you to change the perspective on a photo. This function doesn't work with Smart Objects, so it's best to duplicate the original layer with <span class="command">Option-⌘-J</span>. Make sure to name all your layers.

  Choose <span class="command">Edit > Perspective Warp...</span> Define perspective of the image by dragging out a perspective plane.

  <img class="size75" alt="photoshop-transforms-perspective-controls" src="/images/photoshop-transforms/photoshop-transforms-perspective-controls.jpg">

  Distort the shape of the plane to match the surface in your photo. Drag a plane for each surface.

  Move from the <span class="command">Layout</span> mode to the <span class="command">Warp</span> mode in the Control bar. To straighten the vertical lines, click the first icon in the Control bar. There's a horizontal button to fix horizontal lines. Hold Shift, then hover over the perspective lines. This will constrain the lines while adjusting.

  <img class="size75" alt="photoshop-transforms-perspective-example" src="/images/photoshop-transforms/photoshop-transforms-perspective-example.jpg">

assignment: |
  ### Basic Transforms

  <img class="size100" alt="photoshop-transforms-exercise-1" src="/images/photoshop-transforms/photoshop-transforms-exercise-transform.jpg">

  Open 01-transforms-scale-and-repeat.psd. Perform the transforms on the glass as indicated in the image. You should end up with one glass per layer. Make sure you make each layer a Smart Object to ensure your edits are non-destructive and editable.

  ### Warp Transform

  Open 02-transforms-warp.psd. Use warp envelopes to make the label wrap around the bottle as a Smart Object.

  <img class="size100" alt="photoshop-transforms-exercise-warp" src="/images/photoshop-transforms/photoshop-transforms-exercise-warp.jpg">

  As you can see, there's a glass layer on top of the layer stack, with a Linear Light blend mode. The label was also made more realistic with gentle Gaussian Blur Smart Filter. Paint on the filter's mask to edit it.

  ### Vanishing Point

  Use the Vanishing Point filter to move the banner art onto the wall in perspective.

  <img class="size100" alt="photoshop-transforms-vanishing-exercise" src="/images/photoshop-transforms/photoshop-transforms-exercise-vanishing.jpg">

  As you can see, there's a drop shadow on the sign. You can access this effect from the *fx* button at the bottom of the Layers panel.

  ### Puppet Warp

  Find a photo on which you'll perform a puppet warp. This could change someone's facial expression. It could change their stance or body position. Your effect needs to be realistic, obvious and non-destructive.

  <img class="size100" alt="photoshop-transforms-puppet-warp-before-after" src="/images/photoshop-transforms/photoshop-transforms-puppet-warp-before-after.jpg">

  Realistic: This means that we shouldn't really be able to tell you've modified the photo without looking at the original.

  Obvious: The edits need to be very obvious when we compare the *before* and *after* states.

  Non-destructive: Duplicate your subject onto a new layer. Make that duplicate layer a Smart Object. We want to be able to see the *before* and *after*. We also want to be able to go back into the warp settings to edit them.

  Once you're done, save and close.

  ### Perspective Warp

  Open 04-transforms-perspective-warp.psd. Use the Perspective Warp tool to remove the lens distortion on the building, as shown. Make sure you duplicate the building layer, then make it a Smart Object.

  <img class="size100" alt="photoshop-transforms-perspective-exercise" src="/images/photoshop-transforms/photoshop-transforms-exercise-perspective.jpg">

  Once you're done, save and close.
---
https://www.lynda.com/Photoshop-tutorials/Photoshop-CC-2015-One-One-Fundamentals/373100-2.html

https://www.lynda.com/Photoshop-tutorials/Photoshop-CC-2017-Essential-Training-Design/518165-2.html
