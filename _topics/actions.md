---
layout: submission
type: assignment
formsum: formative
sortorder: 6.0
appsused: psd
title: "Actions"
level: undetermined
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=189395&grpid=0&isprv=0&bp=0&ou=227625"
submission: "my-assignment-folder"
links:
downloads: "https://www.dropbox.com/s/gigiehzqkjch9vr/photoshop-actions.zip?dl=1"
description: "Performing repetitive tasks on your computer can cause errors and be really tedious. Automator is an often ignored app which can save you a ton of time."
details: |
  ### Why Use Actions?

  There are quite a few tasks a Photoshop user is required to do on a regular basis. Tasks like sharpening or resizing photos are done really often. Well, imagine if you could create your own custom sharpening workflow that's triggered with the click of a button. That's what Photoshop Actions bring to the table

  When you click the <span class="command">Record</span> button at the bottom of the Actions panel, Photoshop will record all the menus you access, all the buttons you click and all the values you enter. It will *not* record some things, like painting with a brush or the passage of time while it's recording.

  ### The Actions Panel

  The Actions panel contains sets. In the sets are the individual actions. In the actions are the steps you've recorded.

  <figure>
  <img class="size33" alt="photoshop-actions-panel" src="/images/photoshop-actions/photoshop-actions-panel.jpg">
  <figcaption>
  <ol class="width100">
    <li>Stop playing or recording</li>
    <li>Begin recording</li>
    <li>Play Selection</li>
    <li>Create a new set</li>
    <li>Create a new Action</li>
    <li>Delete</li>
  </ol>
  </figcaption>
  </figure>

  This is my current Actions panel. You can see my actions are in a set called Al's Actions.

  If you want a clean panel, you can delete the default set of actions Adobe has included with Photoshop. They're really useless.

  ### The Actions Panel

  To create a new Action, click on the button at the bottom of the panel, or use the panel menu.

    <figure>
    <img class="size50" alt="photoshop-new-action-dialogue" src="/images/photoshop-actions/photoshop-new-action-dialogue.jpg">
  <figcaption>
    This is the New Action dialogue.
  </figcaption>
  </figure>

  The *New Action* dialogue allows you to name your action. Choose the actions set you want to store it in. You can attribute a keyboard shortcut to your action. A colour can also be given to the action. This colour shows when you set your Actions panel to Button Mode.

    <figure>
    <img class="size50" alt="photoshop-actions-panel-button-mode" src="/images/photoshop-actions/photoshop-actions-panel-button-mode.jpg">
  <figcaption>
    The Acions panel in button mode.
  </figcaption>
  </figure>

  When the panel is in Button Mode, you simply need to click on an action once to have it play. Notice the Play button isn't even there.

  ### # Our First Action

  Sharpening photos is a common task which lends itself to automation. We'll set up a workflow which runs through a series of actions, but asks for parameters along the way.

  We'll use the *Sharpen with High Pass* technique to sharpen a photo. All you'll need to do in the future is to hit the <span class="command">Play</span> button in the Actions panel to sharpen any photo.

    <figure>
    <img class="size100" alt="photoshop-actions-panel-sharpen" src="/images/photoshop-actions/photoshop-actions-sharpen-high-pass.jpg">
  <figcaption>
    Sharpen your photos with an action.
  </figcaption>
  </figure>

  Note that the <span class="command">Toggle Dialogue On/Off</span> button is turned on. This makes it that when the action runs, the High Pass dialogue will prompt you for a setting. Every photo needs a different value in the filter, so it's convenient to have this option.

  If you make a mistake while recording an action, you can continue recording, then fix it after. Complete your recording. Target the step with the error, then hit delete. Click the record button, then perform the corrected step. Stop recording. Done!

  ### The Image Processor

  Photoshop's Image Processor is a built-in automation powerhouse. You can batch-export images and much, much more.

  <figure>
      <img class="size75" alt="photoshop-image-processor-dialogue" src="/images/photoshop-actions/photoshop-image-processor-dialogue.jpg">
  <figcaption>
  <ol>
    <li>Feed Image Processor a folder of images.</li>
    <li>Tell Image Processor where to save the output of the processing.</li>
    <li>Choose one or more file formats and settings in which to save your images.</li>
    <li>Run an action on the processed images.</li>
  </ol>
  </figcaption>
  </figure>

  The Image Processor converts and processes multiple files. It lets you process files without first creating an action.

  You can do any of the following in the Image Processor:

  * Convert a set of files to either JPEG, PSD, or TIFF format; or convert files simultaneously to all three formats.
  * Process a set of camera raw files using the same options.
  * Resize images to fit within specified pixel dimensions.
  * Embed a color profile or convert a set of files to sRGB and save them as JPEG images for the web.

  It works with Photoshop (psd), JPEG, and camera raw files.

  #### Image Processor + Actions!

  We've covered Image Processor and Actions on their own. Now let's see how powerful they can be when combined.

  Photoshop's Image Processor is a powerful tool. What really amps up it's juice is the Actions menu at the bottom. On top of changing file types and resizing on the fly, you can have it run an action. Knowing that an action can do pretty much anything in Photoshop, makes the Image Processor your go-to automation tool.

  <figure>
      <img class="size100" alt="photoshop-actions-image-processor-actions" src="/images/photoshop-actions/photoshop-actions-image-processor-actions.jpg">
  <figcaption>
    The Image Processor dialogue. It runs a Gradient Map action, then saves the file as a 500px native Photoshop file.
  </figcaption>
  </figure>

  Let's create a new action that makes the images look monochromatic, with an orange colour cast. We'll use a "Gradient Map" adjustment layer to achieve this.

  We'll apply the Image Processor to the provided photos. While we're at it, let's make the images 500 pixels wide and save them as native .psd files. Save them into the 03-image-processor+actions-output folder.

  ### Batch Workflows

  Once you've recorded a workflow, you can apply it to as many image files as you wish. This is what File > Automate > Batch... does.

    <figure>
    <img class="size75" alt="photoshop-batch-menu" src="/images/photoshop-actions/photoshop-batch-menu.jpg">
  <figcaption>
    Launch a batch workflow on many files.
  </figcaption>
  </figure>

  A single action is very practical for affecting one or a few images. You just open the image, click the <span class="command">Play</span> button in the Actions panel, sit back and watch the magic happen. But what if you have 20 images, or 200, or even 20,000?

  Batch processing is key to applying an action to a large number of images. You set up your action beforehand. Go <span class="command">File > Automate, Batch...</span> In the Batch dialogue, you get options for locating the files and re-naming them.

    <figure>
    <img class="size75" alt="photoshop-batch-dialogue" src="/images/photoshop-actions/photoshop-batch-dialogue.jpg">
  <figcaption>
    The Batch dialogue.
  </figcaption>
  </figure>

  1. Play: Which action are you going to run on all your images?
    * Override action "Open" commands: When checked, this will process the images specified above rather than images your action may ask for.
    * Suppress File Open Options Dialogs: Sometimes, when a file is opened, Photoshop presents a dialogue. When checked, this will suppress that dialogue and continue processing.
  2. Source: Give the command a folder of images to process.
  3. Errors: If Photoshop encounteres a problem while it processes the images, it can log the errors in a text file, then continue with the rest of the images.
  4. Destination: Tell Photoshop where to put the completed images.
  5. File Naming: Set up costom a file naming convention for the processed files.
    * If the action you've recored has a *Save As...* command in it, this option will ignore it. It will save the files where you tell it here, with a custom name.

  Let's run our Sharpen with High Pass action on our source photos. Save them to the the 04-batch-processing-output folder.

  ### Crop & Straighten Photos

  The Crop and Straighten script in Photoshop can be a real time-saver if you have a series of photos you need to crop and straighten.

  If you're in the process of digitizing old photos, you may think you're stuck with scanning only one print at a time. Photoshop can help you if you scan more than one.

    <figure>
    <img class="size75" alt="photoshop-scan" src="/images/photoshop-actions/photoshop-scan.jpg">
  <figcaption>
    Six photos scanned at once. All askew.
  </figcaption>
  </figure>

  Place as many images on your flatbed scanner as can fit. It doesn't even matter if they move a bit when you close the lid. Just make sure the photos aren't overlapping. Go ahead and scan your photos into one file.

  Once you have your scan, you can use <span class="command">File > Automate > Crop and Straighten</span>. This script will magically create a separate file with each photo in it.

    <figure>
    <img class="size75" alt="photoshop-crop-and-straighten-output" src="/images/photoshop-actions/photoshop-crop-and-straighten-output.jpg">
  <figcaption>
    Crop and Straighten output. All photos straightened.
  </figcaption>
  </figure>

  The one condition for this to work is that the backgrounds of the photos are not completely white. When Photoshop produces the separate file, it detects the edges of each one. If the background of your photo is completely white, it may not be able to differentiate it from the scanner's white lid.

  Run the script on the 05-crop-and-straighten.jpg photo. Save the resulting images in the 05-crop-and-straighten-output folder.

  ### Using Photomerge

  Photoshop includes a function called Photomerge. It's under the <span class="command">File > Automate</span> menu. It receives a series of photos. Your source photographs play a large role in panoramic compositions. You need to have enough overlap between the photos for Photoshop to know how to stitch them together.

  <figure>
    <img class="size100" alt="photoshop-actions-photomerge" src="/images/photoshop-actions/photoshop-actions-photomerge.jpg">
  <figcaption>
    This is how you use Photoshop's Photomerge feature to create a panorama.
  </figcaption>
  </figure>

  Create a panorama with the photos in the 06-photomerge > 00-photos-to-merge folder. Save the resulting file in the 06-photomerge folder.

  ### Creating a Droplet

  A droplet is a file you can keep anywhere on your computer. When you drop image file on it, it will perform a workflow. A droplet applies an action to one or more images, or a folder of images that you drag onto the droplet icon.

  <img class="size15" alt="photoshop-actions-photomerge" src="/images/photoshop-actions/photoshop-droplet.svg">

  Actions are the basis for creating droplets — you must create the desired action in the Actions panel before creating a droplet.

  1. Choose <span class="command">File > Automate > Create Droplet</span>.
  2. Specify where to save the droplet. Click <span class="command">Choose</span> in the *Save Droplet In* section of the dialogue box and navigate to the location.
  3. Select the Action Set, and then designate which action you intend to use within the Set and Action menus. Select the action in the Actions panel before you open the dialog box to pre-select these menus.
  4. Set processing, saving, and file naming options.

  Let's create a droplet which will perform the *Sharpen with High Pass* workflow on our photos.

  <figure>
    <img class="size100" alt="photoshop-actions-create-droplet" src="/images/photoshop-actions/photoshop-actions-create-droplet.jpg">
  <figcaption>
    The Create Droplet dialogue.
  </figcaption>
  </figure>

  Save the droplet in the 07-droplet folder. Run the sharpening workflow. Log your errors to a text file in the same folder. Output the resulting files into the provided 00-droplet-output folder.

  <img class="size75" alt="photoshop-actions-create-droplet-locations" src="/images/photoshop-actions/photoshop-actions-create-droplet-locations.jpg">

  #### Processing files with droplets

  Drag files or a folder of images onto the droplet icon. Photoshop will launch if it is not already running. It will open and process each file, one after the other. You can work in other applications while it's running, but they will likely perform more slowly, since Photoshop is working as hard as it can.

  <div class="attentionbox tip">
    Remember that Automator can do many simple tasks Photoshop can. The added benefit is that it doesn't open the images. It's more limited, but it runs much, much faster.
  </div>

  #### Back Up Droplet Actions

  A droplet is based on an action. Let's say you create your action, then create a droplet. You delete the action from the panel. You then lose the droplet. You'll need to re-record the action to create the droplet from it.

  <img class="size15" alt="photoshop-actions-saved-file" src="/images/photoshop-actions/photoshop-actions-saved-file.jpg">

  In order to not lose anything, record the action, then go to the panel menu. Choose <span class="command">Save Action...</span>. This will save a file on your computer with the whole set of actions in it, which you can re-load in the panel.

  ### Creating Contact Sheets

  Contact sheets can be used to aid photo selection after a shoot. They can be presented to clients for approvals. In other words, they're very convenient to have around. The challenge is that creating them manually would be very tedious.

  The dialogue is big, but pretty easy to use. The options are clear. Note that you can preserve layers, which makes the contact sheet easily editable.

  <figure>
      <img class="size100" alt="photoshop-actions-contact-sheet" src="/images/photoshop-actions/photoshop-actions-contact-sheet.jpg">
  <figcaption>
    Run the Contact Sheet script on the provided photos. Save it to the 08-contact-sheet folder.
  </figcaption>
  </figure>

  Run the Contact Sheet script on the provided images. Save the resulting files into the 08-contact-sheet folder.

assignment: |
  ### Image Processor

  1. Feed the Image Processor dialogue the source images.
  2. Convert the images to jpeg, psd and tiff files.
  3. Resize the images to 512 pixels.
  4. Do nothing in the section 4 at the bottom of the dialogue.
  5. Have the processed photos put in the 01-image-processor-output folder.

  ### Crop & Straighten

  Run the Crop & Straighten script on the 02-crop-and-straighten.psd image. Save the results in the 02-crop-and-straighten-output folder.

  ### Photomerge

  Use the images in 06-photomerge > 00-photos-to-merge to create a panorama using Photomerge. Let's turn on <span class="command">Content Aware Fill Transparent Areas</span>.

  <img class="size100" alt="photoshop-actions-photomerge" src="/images/photoshop-actions/photoshop-actions-photomerge.jpg">

  Save the resulting panorama into the 03-photomerge > 00-photos-to-merge folder.

  ### Contact Sheet

  Create a contact sheet with the provided photos. Save the file(s) in the 04-contact-sheet folder.
---
