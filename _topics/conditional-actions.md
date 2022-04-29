---
layout: submission
type: assignment
formsum: formative
sortorder: 6.1
appsused: psd
title: "Conditional Actions"
level: undetermined
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=189396&grpid=0&isprv=0&bp=0&ou=227625"
submission: "my-assignment-folder"
links: |
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/conditional-actions-creative-cloud.html" target="_blank" title="x">Conditional Actions</a>
downloads: "https://www.dropbox.com/s/7vwjuzxer3atc95/photoshop-conditional-actions.zip?dl=1"
description: "You're aware of Actions in Photoshop. Did you know you can create if/then statements which setup conditions before an action is run?"
details: | 
  ### Why Conditional Actions

  Imagine that you have hundreds of varied images. Then imagine that you're tasked with editing only the ones which have a certain characteristic. Finding only those images would be very tedious. You could also overlook some images. Well, Conditional Actions let you build workflows that choose what to do based on one of several available conditions. This means you could target only the desired images based on that given characteristic.

  ### How They Work

  How hypothetical situation has us converting only RGB images to CMYK for production. We'll feed Photoshop a folder of photos that are a mix of colour modes. The action will convert the colour mode of only the RGB images to CMYK. The others will be left un-touched. Greyscale images can be placed in a document for print, so we can leave them alone too.

  To use Conditional Actions, you need to first record the workflow you want to use on the images. In our case, we'll record a *Convert to CMYK* workflow.

  <img class="size50" alt="photoshop-conditional-actions-new-action" src="/images/photoshop-conditional-actions/photoshop-conditional-actions-new-action.jpg">

  All we need to do is go <span class="command">Image > Mode > CMYK</span>, then save and close. <mark>Don't forget to stop recording.</mark> Now we have an action to run with conditions in the next step.

  ### Convert Colour if...

  To apply the workflow to only RGB images, we record a new action. Let's call it *IF RGB Convert to CMYK*. Click <span class="command">OK</span>. Choose Insert Conditional from the Actions panel menu.

  <img class="size50" alt="photoshop-conditional-actions-add" src="/images/photoshop-conditional-actions/photoshop-conditional-actions-add.jpg">

  In the Conditional Action dialog box, choose a condition from the If Current menu. Choose actions from the Then Play Action menu and the Else Play Action menu, and then, click OK.

  <img class="size50" alt="photoshop-conditional-actions-options" src="/images/photoshop-conditional-actions/photoshop-conditional-actions-options.jpg">

  You can also choose None in one of the menus, but not both. You can run an action only if a particular condition is false by choosing None as the Then Play Action and choosing the desired action as the Else Play Action.

  In this case, only images which are in RGB mode will be affected.

  Now we need to feed Photoshop our folder of photos. To do so, we'll use <span class="command">File > Automate > Batch...</span>

  #### Testing the opposite of what's in the condition

  There might be instances when you want to test the opposite of what's in a condition.

  For example, suppose you want "Action 1" to play when when the frontmost document is non-square. You would specify the conditional: "If Current Document is Square, Then Play Action None, Else Play Action "Action 1."

  To test for the opposite of a particular condition, swap the "Then" and "Else" actions.
  
assignment: |
  Apply a watermark on the provided photos based on their orientation. Use the provided watermarks. We'll have the conditional actions apply the portrait watermark to the portrait photos and the landscape watermarks to the landscape photos.

  <img class="size100" alt="photoshop-conditional-actions-rulers" src="/images/photoshop-conditional-actions/photoshop-conditional-actions-rulers.jpg">

  Remember to record your action with your rulers set to Percentage. This will make the watermarks scale to the same percentage of the canvas, making the size of your watermark more consistent.

  <img class="size100" alt="watermarked-portrait-landscape" src="/images/photoshop-conditional-actions/watermarked-portrait-landscape.jpg">

  Save them all into the provided folder called watermarked-images.
---
