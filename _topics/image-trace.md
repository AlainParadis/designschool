---
layout: default-nav
type: card
formsum: formative
sortorder: 2.0
appsused: ai, macos
title: "Image Trace"
level: cg2
brightspace:
submission:
links: |
  - Adobe: <a href="https://helpx.adobe.com/illustrator/using/image-trace.html" title="Image Trace" target="_blank">Image Trace</a>
  - Adobe: <a href="https://helpx.adobe.com/illustrator/atv/cs6-tutorials/new-image-trace.html" title="Image Trace Video" target="_blank">Image Trace Video</a>
video: "https://www.youtube.com/embed/myOzR2TQWQY?list=PL4qBMvigUSLDGk988g2BxIS96BJT6ZDO_"
downloads: "https://www.dropbox.com/s/8y9rihtajtabdwx/illustrator-image-trace-live-paint.zip?dl=1"
description: "Adobe have designed a wonderful workflow for getting a sketch off paper into vectors in Illustrator. You can even create multiple colour versions in a matter of seconds. Let's give it a go."
details: |
  ## Why Image Trace?

  The Image Trace feature is part of a workflow that also includes Live Paint and Recolour Artwork. With these three powerful tools, you can create hand-drawn artwork, then transform it into vector art. You can then paint it in colour with Live Paint. The final stage is to create multiple colour variations with Recolour Artwork.

  Together, these tools give you a practical real-world workflow from pencil to final vector artwork.
assignment: |
  ## The Workflow

  Once we've created a sketch of our artwork on paper, we need to scan it. The best scanning application is the one you already have on your Mac. It's called Image Capture.

  Scan your image with the Black & White setting, which should actually be called Greyscale. The resolution isn't actually that important. Sometimes a lower resolution is actually better for tracing. You'll need to experiment with this.

  <figure>
    <img class="size100" alt="image-trace-scan-image" src="/images/illustrator-image-trace-live-paint/image-trace-scan-image.jpg">
  <figcaption>
    Use the Image Capture app that's on your Mac to scan your illustration.
  </figcaption>
  </figure>

  Once you've scanned your drawing, it's a good idea to clean things up and increase the contrast in Photoshop.

  <img class="size100" alt="image-trace-photoshop-prep" src="/images/illustrator-image-trace-live-paint/image-trace-photoshop-prep.jpg">

  You can paint out any stains you may have made while drawing on paper. It's also useful to increase the contrast to ensure the blacks are as dark as possible and the whites are as light as possible. A Levels Adjustment Layer is the best way to do so.

  Create a new letter document in Illustrator. In order to be able to trace our sketch, we need to place it in Illustrator with <span class="command">File > Place</span>.

  <figure>
      <img class="size75" alt="image-trace-place-linked-image" src="/images/illustrator-image-trace-live-paint/image-trace-place-linked-image.jpg">
  <figcaption>
    Use the File > Place command in a new Illustrator document to import the illustration.
  </figcaption>
  </figure>

  <div class="attentionbox tip">
  Never use the Open command from Illustrator to open a raster image. Use File > Place instead.
  </div>

  Make sure that the Link check box is checked in the Place dialogue. This will ensure that there's a link between your Illustrator document and the image file. So, the image should be linked and not embedded. Embedding images is largely frowned upon because it slows down Illustrator's performance a lot.

  Select the image and click <span class="command">Place</span>, you will get a loaded cursor, where you see an icon attached to your cursor. Simply drag a rectangle to the size you want your image. Feel free to re-size your placed image at will. We have no concerns about it's resolution for output. It will be deleted from your Illustrator document in the process of tracing it.

  ## Tracing Images

  Once our image has been placed on an Illustrator Artboard, we'll be ready to Image Trace it.

  <img class="size100" alt="image-trace-image-trace" src="/images/illustrator-image-trace-live-paint/image-trace-image-trace.jpg">

  You can start by selecting your image, then clicking the tiny downward arrow next to the Image Trace button in the Control Panel. This will do an initial tracing of your image. We need to open the tracing options dialogue in order to refine our results.

  We'll dive in to the Image Trace options to make sure we get the most of our image tracing. Keep in mind that what we're seeing in Illustrator is not yet vectors. It's a preview of what our tracing will look like once we're done. If you take a gander at your Links panel, you'll see that your scan is still placed on the page. That needs to be gone by the time we're done.

  Once our tracing looks just right, we'll hit the <span class="command">Expand</span> button in the Control Panel to finally vectorize our tracing.

  <img class="size100" alt="image-trace-finishing" src="/images/illustrator-image-trace-live-paint/image-trace-finishing.jpg">

  You can finish up by smoothing paths, if necessary. Select your vector art. Go <span class="command">Object > Path > Simplify...</span> Go easy. If you simplify too much, you'll distort your illustration. The best plan is to work on a duplicate of your illustration.

  Keep this folder in order to submit it with the <a href="live-paint-recolour.html" title="This is the Live Paint and Recolour Artwork part of this assignment.">Live Paint</a> part of this project.
---
  ## Notes

  * Have them draw a character for next class.
    * They need to make closed paths.
  * In class, we'll Image Trace it.
  * We'll Live Paint.
  * Use Colour Groups and Edit Colours to create multiple colour themes.
