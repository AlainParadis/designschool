---
layout: submission
type: assignment
formsum: formative
sortorder: 5.1
appsused: psd
title: "Selecting"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=381850&grpid=0&isprv=0&bp=0&ou=409084"
submission: "my-assignment-folder"
links: |
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/selecting-marquee-tools.html" target="_blank" title="Marquee Tools">Select with Marquee Tools</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/selecting-lasso-tools.html" target="_blank" title="Lasso Tools">Lasso Tools</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/selecting-color-range-image.html" target="_blank" title="Select Colour Range">Select Colour Range</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/select-area-focus.html" target="_blank" title="Select Focus Area">Select Focus Area</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/create-temporary-quick-mask.html" target="_blank" title="Quick Mask">Quick Mask</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLD-jwtDjjxD_pY4JrgSUHcf"
downloads: "https://www.dropbox.com/s/dgw8s32a7hanvpc/photoshop-selecting.zip?dl=1"
description: "Selecting pixels is central to editing in Photoshop. Leveraging the characteristics of the photo is critical to getting a good selection. From there after, you can target selected pixels for editing. All this is done in a non-destructive workflow."
details: |
  ### Representations of Selections

  We usually visualize the marquee as a selection in Photoshop, but there are other representations of selections. These are them.

  ### Marquee Selections

  Marquee selections are very temporary. They're not saved in files when they're closed. You can select all on your canvas with <span class="command">⌘-A</span>. Deselect everything with <span class="command">⌘-D</span>. <span class="command">⌘-clicking</span> on a transparent layer or a channel selects content.

  <img class="size100" alt="photoshop-marquee-example" src="/images/photoshop-selecting/photoshop-marquee-example.jpg">

  A.K.A. *marching ants*, the marquee is as old as Photoshop. It's actually the poorest of all representations of selections because you cannot tell if the selection is feathered or not.

  Marquee tools are the ones that display a selection with a marquee. All marquee-based tools in Photoshop are:

  <img class="size100" alt="photohsop-marquee-tools" src="/images/photoshop-selecting/photohsop-marquee-tools.jpg">

  #### Important Keyboard Shortcuts

  - D: Set foreground & background swatches to default colours, black & white.
  - X: Switch focus of foreground/background colours.
  - ⌘-Delete: Fill with background colour.
  - Option-Delete: Fill with foreground colour.
  - B: Brush Tool. Right-click with Brush tool for controls.
  - [ &nbsp;  or &nbsp; ] : Make brush smaller or bigger.
  - ⌘-D to deselect
  - ⌘-A to select all

  ### Marquee Tool

  The Marquee Tool can be either rectangular or elliptical. These are some practical tips for dragging with the tool:

  * Hold Shift to constrain proportions.
  * Hold Option drag a marquee from the center.
  * Hold the Space Bar while dragging it to move it on the canvas.
  * While a marquee-based tool is active, you can drag the current selection around on the canvas.
  * Option-drag within a marquee selection to subtract from the selection.
  * Shift-drag outside of a marquee selection to add to it.

  <img class="size100 borderlightgrey1" alt="photoshop-transform-selections-watch" src="/images/photoshop-selecting/photoshop-transform-selections-watch.jpg">

  While you have an active marquee, you can right-click, then choose <span class="command">Transform Selection...</span>. This will allow you to transform the selection with a bounding box. You can zoom while it's active. Once you're done, hit Return to accept your transformation.

  Add a Brightness/Contrast adjustment layer to brighten it up.

  ### Lasso

  #### Lasso Tool

  To use the Lasso Tool, you simply drag it around the canvas. When you drop your mouse, the selection closes itself. As with all the marquee tools, Shift adds and Option subtracts from the selection. 

  #### Polygon Lasso Tool

    <figure>
    <img class="size100" alt="photoshop-selecting-lasso" src="/images/photoshop-selecting/photoshop-selecting-lasso.jpg">
  <figcaption>
  The Polygon Lasso tool is very useful in selecting straight-edged areas on the canvas.  
  </figcaption>
  </figure>

  You don't drag with this tool; you just click from one spot to the next. Hitting the delete key removes the last click. Escape deselects while you're drawing a selection.

  ### Quick Selection

  The Quick Selection tool has pretty much replaced the Magic Wand Tool. It pours a selection onto the image like water. The marquee stops when it detects contrast. The keyboard shortcut for the tool is <span class="command">w</span>.

  <img class="size100" alt="photoshop-quick-selection-options" src="/images/photoshop-selecting/photoshop-quick-selection-options.jpg">

  There are few options for this tool. You simply set it to one of three modes: *New Selection*, *Add to Selection* or *Subtract from Selection*. You can set the tool to add to the selection automatically, as shown above. This is the default I use. You can keep it in the default mode, then hold <span class="command">Shift</span> or <span class="command">Option</span> to respectively add or remove from the selection.

  You can change the size of the Quick Selection brush with the Options Bar, or with <span class="command">[</span> or <span class="command">]</span> keys.

  <span class="command">Auto-Enhance</span> is fairly self-explanatory. Photoshop analyses the selection once you drop it and attempts to improve it. Sometimes this works. Sometimes it does more harm than good.

  As with other tools in Photoshop, you can save all tool presets with the Presets menu in the Control Bar.
  <figure>
  <img class="size100 borderlightgrey1" alt="photoshop-selecting-quick-select" src="/images/photoshop-selecting/photoshop-selecting-quick-select.jpg">  
  <figcaption>
    Use the Quick Select tool to select the guy, then mask him out to reveal an alternate background.
  </figcaption>
  </figure>

  ### Select Colour Range

  Go <span class="command">Select > Colour Range...</span>. You have the choice of sampling colours on the canvas or choosing colours from the dropdown menu.

  <img class="size50" alt="photoshop-select-colour-range" src="/images/photoshop-selecting/photoshop-select-colour-range.jpg">

  The <span class="command">Fuzziness</span> slider determines the tolerance of the selection. That's how little or how much different the colour can be.

  <figure>
      <img class="size100" alt="photoshop-select-colour-range-2" src="/images/photoshop-selecting/photoshop-select-colour-range-2.jpg">
  <figcaption>
  Use Sample Colours. Sample the reddest red from her cheek.    
  </figcaption>
  </figure>
  
  Once Select Colour Range has done its thing, we can add an Adjustment Layer to edit her colour to match the photo.

  ### Select Focus Area

  When you use <span class="command">Select > Focus Area...</span> Photoshop examines the image for sharp and blurry areas. It can output the resulting selection to a mask on a new layer.

  <img class="size100" alt="photoshop-selecting-focus-area" src="/images/photoshop-selecting/photoshop-selecting-focus-area.jpg">

  The first part of the dialogue is simply the preview. Choose the setting you prefer. <span class="command">Parameters</span> allow you to include more or fewer pixels in your selection. <span class="command">Output</span> is what you get once you click <span class="command">OK</span>. The best choice is <span class="command">New Layer with Layer Mask</span>. It's most editable.

  ### Ai Driven Selections
  
  #### Select Subject
  
  The Select Subject is part of Adobe's smart suite of tools that uses artificial intelligence to find content in a photo.
  
    <figure>
  <img class="size100 borderlightgrey1" alt="photoshop-select-subject" src="/images/photoshop-selecting/photoshop-select-subject.jpg">    
  <figcaption>
    Select Subject works really well on high contrast photos with a clear subject.
  </figcaption>
  </figure>

  Select the dude, then mask him to reveal an alternate background in the photo.

  #### Select Object
  
  When the subject of the photo is not as obvious, you can use the Select Object tool to be more specific.
  
  <figure>
  <img class="size100 borderlightgrey1" alt="photoshop-select-object-tool" src="/images/photoshop-selecting/photoshop-select-object-tool.jpg">  
  <figcaption>
    Use the Select Object tool to select the boots.
  </figcaption>
  </figure>

  Once the boots are selected, we can change their colour.

  ### Reversibility of Selections

  <img class="size100" alt="photoshop-selection-reversability" src="/images/photoshop-selecting/photoshop-selection-reversability.jpg">

  If you're attempting to select a very detailed object on a rather flat background, it would likely be simpler to select the background, then invert the selection. That's the nature of selections in Photoshop. They're simple to invert.

  #### Save a Selection

  No matter the selection you create, you can use <span class="command">Select > Save Selection...</span> to create an *Alpha Channel*. This is simply a saved selection. It doesn't show on the canvas. It only appears in the Channels panel. It's saved in your document even after it's closed.

  Any mask you create makes an Alpha Channel, which is saved in your Photoshop file. This includes the mask that comes with an Adjustment Layer.

  ### Clipping Path

  When you want to place an image of a hard-edged object in a page layout without its background, a clipping path is the way to go.

  The Pen Tool takes centre stage in this lesson. We'll use it to draw around an object to hide its background when it's placed in a page layout. The benefit of a clipping path is that it has a sharp edge. It will cut out the object with as clean an edge as possible. Clipping paths are appropriate when the object to be clipped has a hard edge. If your subject has curly hair, a clipping path is not the way to go.

  By the way, <mark>this process has nothing to do with layers</mark>. We're going to draw a path around the object, then save it. We don't delete the background pixels. They just get masked by the path once the image is placed in InDesign.

  #### Clip the Clamp

  <figure>
      <img alt="photoshop-clipping-path" src="/images/photoshop-selecting/photoshop-clipping-path-clamp.jpg" class="size100">    
  <figcaption>
    <ol>
    <li>Use the Pen Tool</li>
    <li>Set the mode to Path</li>
    <li>Set Path Operations as needed</li>
    <li>What's selected is white</li>
    </ol>
  </figcaption>
  </figure>

  Set the Pen Tool's mode to Path and not Shape in the Control bar. Paths in Photoshop don't print by default. It's a path without a stroke. You can even turn on the Rubber Band effect like in Illustrator.

  When you draw your path, use the same Pen tool technique you'd use when drawing in Illustrator. When your object has a hollow centre, like the clamp, make sure the Path Operations is set to <span class="command">Exclude Overlapping Shapes</span>. This will make the paths panel look like the one above. The object needs to be white and the surrounding area grey in the panel.

  Once you're done with drawing the path, save it by double-clicking on it. Then, give it a meaningful name.

  Save your image as a .psd file.

  #### Place in InDesign

  Once you get your image into InDesign, you can use its clipping path options to select which path to use in your document. The interoperability between Photoshop and InDesign really shines. Open the provided InDesign document, then go <span class="command">File > Place</span>.

  <img alt="photoshop-clipping-path-indesign" src="/images/photoshop-selecting/photoshop-clipping-path-indesign.jpg" class="size100">

  Select your image on the page, then go <span class="command">Object > Clipping Path Options...</span>. Choose Photoshop Path from the dropdown. Choose the path's name from the second dropdown. If you check the <span class="command">Preview</span> checkbox, then you'll see the background disappear on the page.

  #### Edit Your Path

  Once you have the job all done in InDesign, you may notice you've either cut it too close or too far from the object. You need to round-trip it from Photoshop to InDesign to fix it. Edit the path in the image. Save it.

  <div class="attentionbox tip">
    You can Option-click on your image in InDesign to open it in Photoshop.
  </div>

  <img class="size33" alt="photoshop-clipping-path-panel" src="/images/photoshop-selecting/photoshop-clipping-path-panel.jpg">

  Go back to InDesign. Check your Links panel to make sure you're looking at the latest version. If you see an exclamation mark like this, simply double-click on it to update it.

assignment: |

  #### Marquee Tool

  Use the Elliptical Marquee Tool on the clock image to select the whole clock. Once you've selected it accurately, add a Hue/Saturation adjustment layer to make it a different colour.

  <img class="size100 borderlightgrey1" alt="selecting-exercise-marquee-tool" src="/images/photoshop-selecting/selecting-exercise-marquee-tool.jpg">

  Save an close the image.

  #### Lasso Tool

  Use the Polygon Lasso Tool to select each of the device screens. Zoom in to start.

  <img class="size100" alt="selecting-exercise-lasso" src="/images/photoshop-selecting/selecting-exercise-lasso.jpg">

  You can use the Hand Tool with the Space Bar to pan around the image. ⌘-plus and ⌘-minus works while you're selecting. Once you've made a selection for one of the screens, add a Layer Mask to the appropriate poster graphic as shown above.

  #### Quick Select

  Use the Quick Select Tool to select her legs and her shoes. Once you have a clean, accurate selection, add a Hue Saturation adjustment layer to change the colour of the legs and shoes.

  <img class="size100 borderlightgrey1" alt="selecting-exercise-quick-select" src="/images/photoshop-selecting/selecting-exercise-quick-select1.jpg">

  #### Colour Range

  Use <span class="command">Select > Colour Range...</span> to select the orange part of the van. We want to make the orange turn to yellow.

  <img class="size100" alt="secting-exercise-colour-range" src="/images/photoshop-selecting/secting-exercise-colour-range.jpg">

  You're not going to get it all with the Colour Range function. Add your Hue/Saturation Adjustment Layer to change the orange to yellow. Paint white or black on the mask to edit it. What's white on the mask will become yellow.

  #### Select Subject
  
  Use the Select Subject feature to select the woman. Once it's done, you can simply mask her. Feel free to refine the mask, or not.

  <img class="size100 borderlightgrey1" alt="secting-exercise-colour-range" src="/images/photoshop-selecting/selecting-exercise-select-subject.jpg">

  #### Select Object Tool

  Use the Select Object tool to select the camera. Add an Adjustment Layer to do something to it.

  <img class="size100 borderlightgrey1" alt="secting-exercise-colour-range" src="/images/photoshop-selecting/selecting-exercise-select-object-tool.jpg">

  #### Select Focus Area

  We're going to mask the guy from the background using <span class="command">Select > Focus Area...</span>. Once the preview looks good enough in the Focus Area dialogue, make sure Output is set to <span class="command">New Layer with Layer Mask</span>.

  <img class="size100" alt="selecting-exercise-focus-area" src="/images/photoshop-selecting/selecting-exercise-focus-area.jpg">

  You can use <span class="command">Select and Mask...</span> to refine the Mask.

  #### Vector Path

  Use the Pen Tool set to <span class="command">Path</span>. Draw around the screen. Target the poster's layer, turn on its visibility. Go <span class="command">Layer > Vector Mask > Current Path</span>. That's it!

  <figure>
      <img class="size100 borderlightgrey1" alt="selecting-exercise-vector-mask" src="/images/photoshop-selecting/selecting-exercise-vector-mask.jpg">
  <figcaption>
    Draw a path around the perimeter of the screen.
  </figcaption>
  </figure>


  #### Clipping Path

  Create a path around the cheese. Don't forget to draw the void in the center.

  <figure>
      <img class="size75 borderlightgrey1" alt="selecting-clipping-path-cheese" src="/images/photoshop-selecting/selecting-exercise-clipping-path.jpg">
  <figcaption>
    Draw a path around the perimeter of the cheeze, then one in the inside void.
  </figcaption>
  </figure>

  Make sure to name your path. Place the photo in the provided InDesign document. The white background should not show in InDesign.

  Save and close the InDesign document.

---
