---
layout: submission
type: card
formsum: formative
sortorder: 3.0
appsused: psd
title: "Smart Objects"
level: cg5
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=86521&grpid=0&isprv=0&bp=0&ou=92682"
submission: "generic-zip-folder"
links: 
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLCHHO2khLLnHHSvukoas8Y6"
downloads: "https://www.dropbox.com/s/q3e7tjzzpc92122/photoshop-mockups.zip?dl=1"
description: "Photoshop mockups are layered files in which you can insert an image of a portfolio piece to show it in its natural environment."
details: | 
  ## Why Mockups?

  The mockups we are referring to here are Photoshop files in which a designer can place their portfolio pieces so they become part of a photograph. They feature your portfolio piece in its natural environment as if it were in daily use.

  There are a plethora of web sites where members of the public can buy templated design solutions, be they brochure or web site templates. You should treat these sites as a source of competition for designers everywhere. What they shouldn't be is a source of graphics for us, designers. We need to be the ones <i>making</i> (and maybe selling) the mockups, not <i>buying</i> them.

  <img class="size75" alt="photoshop-mockup-example" src="/images/photoshop-mockups/photoshop-mockup-example.jpg">

  ## Why Smart Objects?

  A Photoshop Smart Object is the tool used to create the mockup. It allows for the seamless swapping of artwork, while all the transformations, masks and effects are maintained.

  Smart Objects are a special type of layer in Photoshop. They're a container for the original image (or images!). The image can be a photo, vector content or even text. The goals of Smart Objects are to ensure non-destructive editing, to assist team work and to edit duplicate layers simultaneously.

  <img class="size33" alt="photoshop-smart-objects-layers-panel" src="/images/photoshop-smart-objects/photoshop-smart-objects-layers-panel.jpg">

  You know you have a Smart Object by the small icon in the corner of the layer's main icon. There's a chain-link icon for Linked Smart Objects and a page icon for Embedded Smart Objects.

  The reason Smart Objects aid non-destructive editing is that you're not really affecting the pixel data. See, if you scale a Smart Object, you're not really scaling the image. You're scaling an image of the original art. This means that you could scale it up and down repeatedly without damaging the original image's pixels.

  One thing you cannot do to a Smart Object is affect its pixel data by painting in any way.

  ## Some Settings...

  There are a few settings related to Smart Objects you should know about. Go <span class="command">Photoshop > Preferences > General</span> to find these settings.

  <img alt="photoshop-smart-objects-preferences" src="/images/photoshop-smart-objects/photoshop-smart-objects-preferences.jpg">

  Resize Image During Place does just that. If you place an image that's larger than your current canvas, it will resize it to fit the canvas. This prevents a gigantic image's tranform box from being way off screen.

  Always Create Smart Object when Placing is pretty obvious. When you use the <span class="command">File > Place</span> command, the resulting layer is a Smart Object.

  Skip Transform when Placing eliminates the transform box alltogether. You can always envoke the Tranform box with <span class="command">⌘-T</span> if you want to scale your placed Smart Object.

  ## Creating Smart Objects

  ### From Menus

  There are many ways to create a Smart Object. You can right-click on any layer's name and choose <span class="command">Convert to Smart Object</span>. You can also go <span class="command">Layers > Smart Objects > Convert to Smart Object</span>. These commands are both the same. You can also get to the command from the Layers panel menu.

    <figure>
    <img class="size50" alt="photoshop-open-as-smart-object" src="/images/photoshop-smart-objects/photoshop-open-as-smart-object.jpg">
  <figcaption>
    You can also choose to open an image directly as a Smart Object.
  </figcaption>
  </figure>

  The <span class="command">Filters > Convert for Smart Filters</span> command makes a Smart Object too. So really, they're not Smart Filters. They're normal filters being applied to the Smart Object. Either way, this makes it that any filters you apply to a Smart Object are non-distructive. They are applied to an image of the photo; not the original photo.

  ### Placing an Image

  When you use the <span class="command">File > Place</span> command, the placed image is a Smart Object. It's usually best to place .PSD files beccause they have layers. If you place a JPEG, then you do edits that have layers, you need to flatten them every time.
    
  ## Replacing Their Contents

  As stated above, a Smart Object is a container for a photo or vector art. Well, if it's a container, it stands to reason that we can replace the contents of that container.

  <img class="size50" alt="photoshop-smart-objects-replace-contents" src="/images/photoshop-smart-objects/photoshop-smart-objects-replace-contents.jpg">

  With the Marquee tool, right-click on your canvas. You'll see an option for <span class="command">Replace Contents...</span>. You can also access this command by right-clicking on the layer and from the <span class="command">Layers > Smart Objects</span> menu.

  When you replace the contents of a Smart Object, it inherits all the transformations and effects you had previously applied. This is really one of the big benefits of Smart Objects.

  ## Duplicating a Smart Object

  There are two ways to duplicate a Smart Object. One method makes it that all instances of the Smart Object have one source image. The second method creates a whole new Smart Object, with no relationship to the first.

  <img class="size33" alt="photoshop-smart-objects-duplicates" src="/images/photoshop-smart-objects/photoshop-smart-objects-duplicates.jpg">

  By default, all duplicates of a Smart Object have the same source image inside them. When you edit one, all copies reflect the edit. In the image above, I added a mask to one of the layers. The other layer got the mask automatically.

  ### New Smart Object via Copy

  <img class="size50" alt="photoshop-smart-objects-new-via-copy" src="/images/photoshop-smart-objects/photoshop-smart-objects-new-via-copy.jpg">

  When you use the New Smart Object via Copy command, Photoshop creates a separate instance of the Smart Object, which doesn't affect any others.

  <div class="attentionbox tip">
  You can nest Smart Objects! Target multiple smart objects in the layers panel. Right-click on them, then choose Convert to Smart Object. Now you have multiple smart objects inside a single smart object.
  </div>

  ## Linked vs. Embedded Smart Objects

  When you use the <span class="command">File > Place</span> command, you have two choices. You can choose <span class="command">Linked</span> or <span class="command">Embedded</span>. When you choose to embed, the image becomes part of your Photoshop file.

  When you choose to link it, the image behaves as a linked image would in InDesign. There's a link relationship between the main file and the linked file on your computer. The contents of a linked Smart Object are referenced from external image files.

  With linked Smart Objects, you can use a shared source file across multiple Photoshop documents. This is great for working in teams. Imagine three designers each working on files A, B and C, wich each have file D linked to them. When D is edited, it updates in A, B and C like magic. Really. Magic. *Adobe Magic*.

  <img class="size75" alt="photoshop-linked-smart-object-layers-panel" src="/images/photoshop-smart-objects/photoshop-linked-smart-object-layers-panel.jpg">

  Linked Smart Objects really work like linked images in InDesign. If you edit the linked image, it updates in the parent file. Beware! If you move, rename or delete the linked file in Finder, the host file can lose track of it.

  <div class="attentionbox tip">
  If you ⌥-drag an image file from Finder into a Photoshop canvas, it will automatically become a Linked Smart Object.
  </div>

  You may have noticed that there's a <span class="command">File > Package</span> command in Photoshop. The function is used to package linked Smart Objects, just like the Package function works in InDesign. And that's all it's good for. It doesn't package fonts or anything else.

  ## Rasterize a Smart Object

  You can convert a Smart Object to a regular layer by simply right-clicking on it in the layers panel, then choosing <span class="command">Rasterize Layer</span>. As usual, this command is also available from the Layer menu, or with a right-click while using the Marquee tool. Once you've done so, the layer's tranformations become destructive.

assignment: |
  ## Our First Device Mockup

  In our first mockup, we want to place artwork on the screen of an iPad. We have the photo of the iPad, then we have a separate .psd of a poster we've designed. To place artwork on a device screen, follow the steps below.

  <img class="size100" alt="photoshop-mockup-process" src="/images/photoshop-mockups/photoshop-mockup-process.jpg">

  You can use any of the transform types shown in step 3. Whatever works for your circumstances. In step #5, you should detach the mask from the image by deactivating the chain-link icon in the Layers panel. This allows us to move the artwork separately inside the mask for proper positioning.

  ## Our First Fabric Mockup

  In order to make artwork conform to the wavy shape and texture of of a fabric, we need to use Photoshop's Displace filter.

  <img class="size75" alt="photoshop-displace-original-burlap" src="/images/photoshop-mockups/displace/photoshop-displace-original-burlap.jpg">

  This is our original untouched image that we'll map the logo to.

  <img class="size75" alt="photoshop-displace-bw-adjustment-layer" src="/images/photoshop-mockups/displace/photoshop-displace-bw-adjustment-layer.jpg">

  We need to create a greyscale version of the burlap to use as a bump map. The best way to do this is to create a Black and White Adjustment Layer. Usually the Infrared setting gives you the highest contrast. If it doesn't work for you, choose another preset. We're looking for the whitest whites and the darkest blacks possible.

  <img class="size33" alt="photoshop-displace-convert-to-grey" src="/images/photoshop-mockups/displace/photoshop-displace-convert-to-grey.jpg">

  Convert your file to greyscale mode. Photoshop will ask you to flatten layers and discard colours. It's all good. We're going to discard these changes anyways.

  <img class="size50" alt="photoshop-displace-save-a-copy-in-grey" src="/images/photoshop-mockups/displace/photoshop-displace-save-a-copy-in-grey.jpg">

  Use <span class="command">Save As...</span>, then make sure that <span class="command">As a Copy</span> is checked so that it spawns a second copy of the file. This will leave the original file untouched. We wouldn't want to convert our original file. Once you've done this, undo back to the colour version of the file.

  <img class="size75" alt="photoshop-displace-drag-in-vector-file" src="/images/photoshop-mockups/displace/photoshop-displace-drag-in-vector-file.jpg">

  Drag any file from Finder into your Photoshop canvas. You can also use <span class="command">File > Place Embedded...</span> to import artwork to map to the background texture. Either way, these methods create a Smart Object.

  <img class="size50" alt="photoshop-displace-filter-displace" src="/images/photoshop-mockups/displace/photoshop-displace-filter-displace.jpg">

  The Displace filter makes our logo inherit the texture of the bump map we give it.

  <img class="size50" alt="photoshop-displace-filter-settings" src="/images/photoshop-mockups/displace/photoshop-displace-filter-settings.jpg">

  The settings you enter in the Displace filter really depend on the resoution of your file. Notice that the number doesn't even have a unit of measure. It's not pixels or percent. We're going ol' school here. Giv'er a number. Take a guess. This is exactly why we're using a Smart Object. It allows us to go back into the settings to make the effect look just right.

  <img class="size100" alt="photoshop-displace-final" src="/images/photoshop-mockups/displace/photoshop-displace-final.jpg">

  We can finish this off by changing the blend mode for the logo's layer. In this case, the logo's black on a lighter backgroud, so the Overlay blend mode works pretty well.

  If you want to add a colour to the logo, use a <span class="command">Colour Overlay</span> Layer Effect.
---
