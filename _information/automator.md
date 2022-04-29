---
layout: default
type: informational
formsum:
sortorder:
appsused: macos
title: "Automator"
level: info
brightspace:
submission:
links: |
  - Apple Support: <a href="https://support.apple.com/guide/automator/welcome/mac" class="">Automator</a>
downloads:
description: "Performing repetitive tasks on your computer can cause errors and be really tedious. Automator is an often ignored app which can perform the same work faster and without errors."
details: |
  ### How Otto Works

  You don't have an employee on which you can hand off tedious tasks like renaming hundreds of files or resizing a folder full of images. Well, actually now you do have one. Otto will save time and he won't make any mistakes.

  <img class="size50" alt="automator-meet-otto" src="/images/macos-automator/automator-meet-otto.jpg">

  The Automator app creates documents. Each time you go <span class="command">File > New</span>, it will create a new document, then ask you what type of automation you wish to create. This is what this looks like.

  <img class="size100" alt="automator-new-document" src="/images/macos-automator/automator-new-document.jpg">

  1. Library: These are the areas that Automator can automate.
  2. Actions: These are all the actions Automator can do.
  3. Types: These are the different types of automations.
  4. Workflow: This is where you stack actions so that they run sequentially.
  5. Description: This is where Automator describes the action you've targeted.
  6. Log or Variables: This area displays a log of your workflow after it has run. It's also the variables area.

  To create a workflow, drag one or more actions into the workflow pane. The order in which you stack them counts because one action feeds the next. If your workflow doesn't work, there will be an error message in the Log pane at the bottom of the window.

  #### Types of Automations

  Workflows:
  : These are the simplest types of automation. Simply drag actions into the workflow pane, then click the <span class="command">Run</span> button.

  Application:
  : This creates a macOS application from your workflow. You double-click on its icon like any other app and your workflow will run.

  Service:
  : This makes your workflow accessible from a right-click menu in Finder.

  Print Plugin:
  : Workflows created from here are accessible from within the Print dialogue.

  Folder Action:
  : These workflows are attached to a folder so that it's run when you add something to the folder.

  Calendar Alarm:
  : These are scheduled workflows. Create the workflow, then schedule it in Apple's Calendar app. So, they can be recurring.

  Image Capture Plugin:
  : Workflows are applied to images from within the Image Capture application.

  Dictation Command:
  : This makes your automation workflows triggerable with speech commands.

  <div class="attentionbox tip">
  If you discover that you've chosen the wrong type of automation, you can always change it after the fact by going <span class="command">File > Convert To...</span>, then choose the type you want.
  </div>

  ### A Simple Workflow

  Let's rename a large number of files using a simple workflow. Launch Automator, then choose to create a new workflow. Save it into the provided <span class="command">01-simple-workflow</span> folder named *Rename Finder Items.workflow*.

  <img class="size15" alt="automator-workflow-icon" src="/images/macos-automator/automator-workflow-icon.jpg">

  All you need to do is drag all the provided files into the workflow pane for Automator to act only on these files. It will add its own <span class="command">Get Specified Items</span> action.

  <img class="size100" alt="automator-workflow-rename-finder-items" src="/images/macos-automator/automator-workflow-rename-finder-items.jpg">

  Do a search for *rename*. Drag the <span class="command">Rename Finder Items</span> action into your workflow. Set it up as shown above. This means you'll drag it in a few times. You can see that we're going to make the file names lower case. We'll replace all spaces and underscores with hyphens. 

  So, this

  Text File 31.txt

  will become this

  text-file-31.txt.

  Do you see how this could be useful for web design? All your web site pages and images should be named without spaces and all lower case. Now you don't need to do this manually anymore. Otto can act on many files at once for you.

  Save this workflow file into the <span class="command">01-simple-workflow</span> folder named *Rename Finder Items.workflow*.

  ### A Finder Service

  <img class="size15" alt="automator-finder-service-icon" src="/images/macos-automator/automator-finder-service-icon.jpg">

  The above workflow is all well and good, but it's quite a bit of work to create such a workflow each time you want to rename files and folders. To this end, we'll create a *Finder Service*.

  Let's create a Finder Service which we can envoke with a right-click in Finder. We'll make it a workflow that we can have rename files and folders however we want.

  <img class="size100" alt="automator-finder-service" src="/images/macos-automator/automator-finder-service.jpg">

  Save this file as <span class="command">Rename Finder Items</span>. You don't choose the location where it's saved. All Finder Services are stored in <span class="command">Home Directory > Library > Services</span>. If you need to edit your service, you can find it there, then open to edit.

  <img class="size100" alt="automator-finder-services-finder-menu" src="/images/macos-automator/automator-finder-services-finder-menu.jpg">

  To envoke the action, simply right-click on files and/or folders in Finder. Go <span class="command">Services > Rename Finder Items</span>. The beauty of this is that the action asks you how you want to rename the selected files. The action asks because you've checked <span class="command">Show this action when the workflow runs</span> when you created the service.

  ### Make Web Friendly Service

  Let's make a *Make Web-Friendly* service so you can quickly renamed batches of files for your web dev projects. Create a new Automator document. Add these actions:

  1. Rename Finder Items: Replace a Space character with a hyphen.
  2. Rename Finder Items: Replace and Underscore character with a hyphen.
  3. Rename Finder Items: Make the whole file name lower case.

  Save the Automator document as Make Web-Friendly. Now, when you need to rename a batch of files or folders, you can do it with a right-click.

  ### A Folder Action

  <img class="size15" alt="automator-folder-action-icon" src="/images/macos-automator/automator-folder-action-icon.jpg">

  You can create an Automator workflow, then attach it to a specific folder. When you add files to the folder, the action does its thing.

  <div class="attentionbox tip">
  Folder Actions are stored here: <span class="command">/Users/*username*/Library/Workflows/Applications/</span>
  </div>

  Let's create an workflow which will resize images. The workflow is meant for really large image files which you want to make smaller to post online or send via e-mail.

  <img class="size100" alt="automator-folder-action-resize-images" src="/images/macos-automator/automator-folder-action-resize-images.jpg">

  <mark>Note that this workflow is destructive.</mark> It's going to resize the originals of any images you put in the folder. Point the action to the provided 02-images-to-1500px folder. Copy the provided images into that folder, then watch the magic happen. All images copied into this folder will be resized to 1500 pixels wide. *-1550px* will be appended to the file names, then they get moved to the 03-processed-images folder.

  You can edit a Folder Action after the fact by right-clicking on the folder itself.

  <img class="size75" alt="automator-edit-folder-action" src="/images/macos-automator/automator-edit-folder-action.jpg">

  On the left is a list of folders on your computer which have actions attached to them. On the right is a list of all the folder actions you've created.

  ### A Calendar Action

  <img class="size15" alt="automator-calendar-action-icon" src="/images/macos-automator/automator-calendar-action-icon.jpg">

  You can create a workflow, then have it triggered by a calendar event. Let's set up a backup schedule for a specific folder. This workflow will copy a folder from one place to another daily.

  <div class="attentionbox tip">
  Calendar Actions are stored here: <span class="command">/Users/*username*/Library/Workflows/Applications/</span>
  </div>

  <img class="size100" alt="automator-calendar-action" src="/images/macos-automator/automator-calendar-action.jpg">

  As you can see, the workflow copies the files from the original location to the folder called <span class="command">03-backup-destination</span>. Once you save the workflow, the Apple Calendar app launches. It allows you to enter the time and frequency of the backup action.

assignment: |

  Read through all the instructions for each workflow, then create it.

  ### A Simple Workflow

  Create a simple workflow that will:

  1. Get text content of your clipboard.
  2. Use Text to Audio File to convert text to audio into our <span class="command">00-your-automator-files</span> folder with the voice of *Alex*.
  3. Add an action that will have the file open in the QuickTime app.

  Save this workflow file into the <span class="command">00-your-automator-files</span> too. Name the workflow *Text-to-Audio.workflow*.

  Copy the text below, then use it in the action.

  > If I die of Vanity, promise me, promise me. That if they bury me some place I don't want to be. That you'll dig me up and transport me. Unceremoniously away from the swollen city breeze, garbage bag trees. Whispers of disease, and acts of enormity. And lower me slowly, sadly, and properly. Get Ry Cooder to sing my eulogy. At the hundredth meridian.

  Save the resulting audio file into your <span class="command">00-your-automator-files</span> folder named *Hip.aiff*.

  ### A Finder Service

  Create a Finder Service which will combine PDF files you select in Finder. Use the provided PDF files -- all 100 of them -- to combine into one file. Name it <span class="command">Combined.pdf</span>. Put it in the <span class="command">00-your-automator-files</span> folder.

  Note that after you've added an action to combine the PDF files in Finder, you'll need an action to open that file. Once it's opened, save it manually into your <span class="command">00-your-automator-files</span> folder named *Combined.pdf*.

  <img class="size33" alt="automator-finder-service-context-menu" src="/images/macos-automator/automator-finder-service-context-menu.jpg">

  Take a screen shot of your context menu by using <span class="command">⌘-Shift-4</span>, then draw a marquee around the menu. The image will appear on your Desktop. Rename it *Combine PDFs.png*. Move it in the <span class="command">00-your-automator-files</span> folder too.

  ### A Folder Action

  Create a folder action which will apply Quartz effect to your photos. Use the images you have in your <span class="command">02-images-to-1500px</span> folder. Apply a Quartz effect of your choice on a copy of these images. So...

  1. Create a Folder Action workflow and give it the <span class="command">00-attach-quartz-workflow</span> folder to attach to.
  2. Add the required actions to your workflow add the Quartz effect.
  3. Add an action which will move the processed photos into the <span class="command">01-quartz-processed</span> folder.
  3. Save the workflow as the name of the effect. So, <span class="command">make-images-sepia</span> or something like this.
  4. In Finder (not in Automator), <mark>Copy</mark> the photos from the <span class="command">02-images-to-1500px</span> into the <span class="command">00-attach-quartz-workflow</span> folder.
  

  I'll know you've completed the task because there will be images in the folder with an effect on them.

---
http://www.macworld.com/article/2834532/ok-mac-using-automators-dictation-commands-new-in-yosemite.html

http://www.macworld.com/article/1131450/software-development/feb08geekfactor.html
