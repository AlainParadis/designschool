---
layout: default-nav
type: card
formsum: formative
sortorder: 3.0
appsused: ai
title: "Intro to Perspective"
level: CG4
brightspace: "https://brightspace.algonquincollege.com/d2l/home"
submission: "generic-zip-folder"
links:  |
  - Adobe: <a href="https://helpx.adobe.com/illustrator/using/perspective-drawing.html" target="_blank" title="Perspective Drawing">Perspective Drawing</a>
  - Adobe: <a href="https://helpx.adobe.com/illustrator/using/perspective-grid.html" target="_blank" title="Define Perspective Grids">Define Perspective Grids</a>
  - Lynda: <a href="https://www.lynda.com/Illustrator-tutorials/Perspective-Drawing-Illustrator/186123-2.html" target="_blank" title="Drawing in Perspective">Drawing in Perspective</a>
video: "https://www.youtube.com/embed/RVcfJ5IUecY?list=PL4qBMvigUSLD4VDB3I0iBnwrnfjnZiEjQ"
downloads: "https://dl.dropboxusercontent.com/u/3084706/downloads/illustrator-drawing-in-perspective.zip"
description: "Drawing in perspective is really rewarding. In this unit, we'll explore the different types of perspective available to us."
details: |
  In this lesson, we'll learn how to use the perspective drawing tools in Illustrator.

  <img class="size75" alt="illustrator-perspective" src="/images/illustrator-perspective/illustrator-perspective.jpg">

  ## Types of Perspective

  Illustrator allows for the three types of perspective illustration. See the image below for a visual of one-point, two-point and three-point perspectives.

  <img class="size100" alt="illustrator-perspective-types" src="/images/illustrator-perspective/illustrator-perspective-types.jpg">

  #### One Point Perspective

  * 1 ground plane
  * 1 vertical plane

  One-point perspective is used when you're point of view is straight-on the subject. Horizontal and Vertical guides are parallel. Depth lines go towards one vanishing point.

  #### Two-point perspective

  * 1 ground plane
  * 2 vertical planes
  * Vertical planes are parallel.

  Two-point perspective is used most commonly. It's point of view is off at an angle. Vertical guides are parallel. Left and right plane guides each lead to a vanishing point on the horizon line.

  #### Three-point Perspective

  * 1 ground plane
  * 2 vertical planes
  * Vertical planes are not parallel.

  This is the same as a two-point perspective, except that the vertical planes are not parallel. This gives your constructions an added sense of *strength*.

  If you want to change type of perspective, go <span class="command">View > Perspective Grid</span>. If you've already drawn art in one type of perspective, if you change perspective, the art won't change.

  ### Parts of the grid.

  <a href="https://helpx.adobe.com/illustrator/using/perspective-grid.html" title="Adobe: Perspective Grid" target="_blank">This is Adobe's explanation</a> of the Perspective Grid. <a href="http://factore.ca/blog/215-perspective-grids-in-illustrator" title="Adobe: Perspective Grid" target="_blank">This one</a> is really good, too.

  <img class="size100" alt="illustrator-perspective-grid" src="/images/illustrator-perspective/illustrator-perspective-grid.gif">

  <div class="attentionbox tip">
  Editing the grid angles can be a finicky process. The Perspective grid presets are burried three menus deep, which is totally annoying. It's often necessary to reset it to a default position, then start editing again. To that end, we'll record an action to reset the grid.
  </div>

  ## Adjusting the Grid

  The grid is central to drawing in perspective. We'll deconstruct the grid and adjust it to suit our needs. Adjust the grid with the Perspective Grid Tool.

  1. The first action to take is to center the grid origin to the bottom center of the shape.
    * The ground plane can be adjusted with three different widgets. The centre, left & right.
  2. Step two is to adjust the height of the grid from the top-center.
  3. Adjust the height of horizon.
    * The Horizon Line is adjustable with the widgets all the way at the ends of the Horizon Line.
  4. Lastly, widen the vanishing points so the left and right planes fit what you want.

  Once it's adjusted, those parameters can be saved under <span class="command">View > Perspective Grid > Save Preset</span>.

  The Perspective Grid can be moved from one Artboard to another. Hover the Perspective Grid Tool over the Ground Plane widget, then drag.

  ## Actually Drawing

  Drawing in perspective isn't much different than normal drawing. As long as the one of the planes are targeted on the .

  ### Plane Switching widget.

  <img class="size33 center" alt="illustrator-perspective-grid" src="/images/illustrator-perspective/perspective-tools-icons.svg">

  The Perspective Grid Tool allows you to manipulate the grid itself. The Perspective Selection Tool allows you to select and edit artwork in perspective.

  <img class="size50 center" alt="illustrator-perspective-grid" src="/images/illustrator-perspective/perspective-widget.svg">

  Click on one side of its cube to draw on that plane on the page. Click just outside of the cube in the widget to deactivate perspective drawing. When drawing on the various planes, Illustrator's regular stacking order is respected.

  You can attach existing artwork to the perspective grid. Select the artwork, then go to <span class="command">Object > Perspective > Attach to Active Plane</span>. This can yield unexpected results. The better way to do it is to use the Perspective Selection Tool to simply drag artwork onto the active plane.

  Artwork can be released from the Perspective Grid. Use the regular Move Tool to move artwork in 2 dimensions. You can also go to <span class="command">Object > Perspective > Release with Perspective</span>.

  <div class="attentionbox tip">
  Power Tip: You can also move or copy artwork perpendicular from its plane by holding the 5 key while draging. Hold Option-5 while dragging to copy.
  </div>

  ### First Practice Drawing

  <img class="size75" alt="illustrator-perspective" src="/images/illustrator-perspective/illustrator-perspective.jpg">

  Let's practice drawing simple artwork in each type of perspective. 1, 2 and 3 point perspectives. Keep in mind that you can only display one grid system at a time. Create one Artboard, then draw your artwork. Create a second artboard. Choose a different perspective system, then draw on it. Do this a third time. When you return to the original artboard and turn on the Perspective Grid, it will be in the right configuration for that artwork.

  ### Symbols in Perspective

  Create an Artboard with a two-point perspective. Draw what looks like a simple building. We'll create a Symbol to draw the windows on the building. We'll only need to draw one initial shape, then we'll be able to edit them all at once.

  ### Adding Type in Perspective

  <img class="size75" alt="illustrator-perspective" src="/images/illustrator-perspective/illustrator-perspective.jpg">

  To add type in perspective, you need to first create it in 2D. Use Point Type -- so just click with the Type tool and type. Don't drag a box. Once you have some type, drag it onto the grid with the Perspective Selection Tool. To edit text which is in perspective, select it with the Perspective Selection Tool. Go to the Options Bar and click on <span class="command">Edit Text</span>. To move type in perspective, use the Perspective Selection Tool and drag.

    * To move perpendicular to the grid, hold the number 5 key while dragging.
    * To move artwork by a specific amount, select it, then double-click on the Perspective Plane Widget.
    * A temporary new plane grid can be displayed by Shift-clicking on an Anchor Point with the Perspective Grid Tool.

  Symbols can be used in perspective. As usual, double-click on the Symbol instance, edit, then hit Escape to get out of Isolation Mode. All Symbol instances will update.

  To move artwork along with the Perspective Grid, go <span class="command">View > Perspective Grid > Lock Station point</span>. Drag a Vanishing Point. The artwork will move with it, though some more complex details may not respect the move.

assignment: |
  Draw in perspective to match the provided building photo. Your goal is to match the perspective of the building. Draw windows as Illustrator symbols. It doesn't matter if you don't match everything exactly. The goal is to get the pespective right.
---
* Create an Action to reset the grid to 1, 2 and 3 point perspectives.
* You can see grid options in Define Perspective Grid.
* Create a 1 Point Perspective. Draw rail road tracks.
* Create a 2 Point Perspective. Draw a cube.
  * Put type on the cube. Edit type.
  * Create a Symbol for a window.
  * Edit the Symbol.
* Record an Action to reset grid to 2 Point Perspective.
* Place a building to trace.
  * Edit grid to match the building.