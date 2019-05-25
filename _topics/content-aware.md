---
layout: submission
type: card
formsum: formative
sortorder: 3.0
appsused: psd
title: "Content Aware"
level: cg4
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=123819&grpid=0&isprv=&bp=0&ou=145538"
submission: "psd-files-in-folder"
links: |
  - <a href="https://helpx.adobe.com/photoshop/using/content-aware-patch-move.html" target="_blank" title="x">Content-Aware Patch & Move</a>
  - <a href="https://helpx.adobe.com/photoshop/using/content-aware-scaling.html" target="_blank" title="Content-Aware Scale">Content-Aware Scale</a>
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/create-panoramic-images-photomerge.html" target="_blank" title="Photomerge">Photomerge</a>
video: "https://www.youtube.com/embed/6WVh4dz_zt4?rel=0"
downloads: "https://www.dropbox.com/s/ypc0ff2irknva21/photoshop-content-aware.zip?dl=1"
description: "Content-Aware tools intelligently fill areas of a photo with a seamlessly background. These tools appear throughout Photoshop. We'll discover the many ways it can be used."
details: |
  Did your annoying uncle photobomb your best party pic? Let's learn how to remove unwanted elements in a photo, so Uncle Hamish doesn't put a damper on your next shindig.

  Photoshop's Content Aware tools are really good at filling in the background of a photo when you either delete or move an element. This is what Adobe has to say about Photoshop's Content-Aware feature:

  > Content-Aware seamlessly fills the selection with similar image content nearby. For the best results, create a selection that extends slightly into the area you want to replicate. (A quick lasso or marquee selection is often sufficient.) <cite><a href="https://helpx.adobe.com/photoshop/using/filling-stroking-selections-layers-paths.html#content_aware_pattern_or_history_fills" target="_blank" title="Adobe: Content-Aware Fill">Adobe</a></cite>

  <div class="attentionbox achtung">
    Before performing any of these operations, it's important to duplicate the original layer, so we preserve our non-destructive workflow.
  </div>

  ## Content-Aware Fill

  Content-Aware fill is great for either deleting or moving elements in a photo.

  ### Delete an Element

  In the image below, we want to erase the wires, the path and the fence. Select them with the Lasso Tool. Hit Shift-F5 to fill. Remember to duplicate the affected layer before cloning.

    <figure>
    <img class="size100" alt="content-aware-fill" src="/images/photoshop-content-aware/content-aware-fill.jpg">
  <figcaption>
    Select the elements of the photo, then use Content-Aware Fill to erase them on a duplicate of the layer.
  </figcaption>
  </figure>

  ### Move an Element

  The microphone in the photo was obviously not positioned at the right location, above the woman. Let's use the Content-Aware Move tool to shift it over. Remember to duplicate the layer before making the edit.

  <figure>
    <img class="size100" alt="content-aware-move" src="/images/photoshop-content-aware/content-aware-move.jpg">
  <figcaption>
    Select the microphone along with some of its surrounding content. Use the Content-Aware Move Tool to scootch it over.
  </figcaption>
  </figure>
  ### Content-Aware Patch

  We can completely remove elements from a photo using the Patch Tool. It uses Content-Aware technology to fill intelligently.

  <figure>
    <img class="size100" alt="content-aware-patch" src="/images/photoshop-content-aware/content-aware-patch.jpg">
  <figcaption>
    Now she's there. Now she's gone. Use the Patch Tool with Content-Aware turned on to preserve the background.
  </figcaption>
  </figure>
  All you need to do is use the Lasso Tool to select around the subject.Switch to the Patch Tool. Set it to Conent-Aware in the Control Bar. Move the subject to a carefully chosen area.

  ## Content-Aware Scale

  Content-Aware Scale allows you to stretch or shrink a photo. It fills in new areas between existing pixels with its best guess of how it should look. This works best with photos that have *low-energy* areas. Use   <span class="command">Edit > Conent-Aware Scale</span> or hit <span class="command">⌘-Option-Shift-C</span> to envoke it.

  <figure>
    <img class="size100" alt="content-aware-scale" src="/images/photoshop-content-aware/content-aware-scale.jpg">
  <figcaption>
    Content-Aware Scale can stretch or shrink a photo, only affecting low energy areas.
  </figcaption>
  </figure>

  ## Content-Aware Crop

  While Content-Aware Scale adds pixels within the photo, Content-Aware Crop adds content on the outside of the photo. It expands the canvas, then fills in that new space intelligently.

  <figure>
    <img class="size100" alt="content-aware-crop" src="/images/photoshop-content-aware/content-aware-crop.jpg">
  <figcaption>
    Content-Aware Crop has added new content to the left of the boys.
  </figcaption>
  </figure>

  ## Photomerge

  Photoshop's Photomerge feature stitches together a series of overlapping photos to create a panoramic composition. You can access it from <span class="command">File > Automate > Photomerge...</span>

    <figure>
    <img class="size100" alt="photomerge-menu-dialogue" src="/images/photoshop-content-aware/photomerge-menu-dialogue.jpg">
  <figcaption>
    Photoshop's Photomerge dialogue
  </figcaption>
  </figure>

  The Content-Aware feature is built right into the Photomerge process. Check the box at the bottom of the dialogue to turn it on.

  <figure>
      <img class="size100" alt="photomerge-content-aware-not-filled" src="/images/photoshop-content-aware/photomerge-content-aware-not-filled.jpg">
  <figcaption>
    This is the panorama without Content-Aware fill applied.
  </figcaption>
  </figure>

  If you turn off the composite layer, you'll see the panorama without Content-Aware filled areas.

  <figure>
    <img class="size75" alt="photomerge-layers-masks" src="/images/photoshop-content-aware/photomerge-layers-masks.jpg">
  <figcaption>
    Photoshop's Photomerge creates masked layers and a composite layer.
  </figcaption>
  </figure>

  The Photomerge function behaves like a good Photoshop citizen, in a non-destructive manner. It saves separate layers with layer masks on each. If you need to, you can edit its work after the fact.

  <figure>
    <img class="size100" alt="photomerge-content-aware-done" src="/images/photoshop-content-aware/photomerge-content-aware-done.jpg">
  <figcaption>
    Content-Aware fill has been applied to the panorama. It's rather seamless.
  </figcaption>
  </figure>
assignment: |
  Use the various Content-Aware tools on the provided photos.

  01-content-aware-fill.psd
  : Remove the wires from the sky on a duplicate of the original layer. Make sure to name all layers for all of these images.

  02-content-aware-move.psd
  : Move the Cuba sign using the Content-Aware Move tool. Move it to the right side of the image.

  03-content-aware-patch.psd
  : Get rid of the girl. Use the Patch Tool with Content-Aware turned on. You can use cloning tools after the fact to edit out any flowers that look like they've been repeated. Just make sure your edits are non-destructive.

  04-content-aware-scale.psd
  : Use Content-Aware Scale to widen a duplicate of the layer with the dude on it. You can actually scale it quite a bit.

  05-content-aware-crop.psd
  : Use Content-Aware cropping to extend the height of the sky and the grass. Be reasonable with the extension size. After a while, Photoshop will create a discernable pattern.

  06-photomerge
  : Create a panorama with the Photomerge feature. Make sure you have Content-Aware turned on.
---
