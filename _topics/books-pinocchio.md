---
layout: submission
type: assignment
formsum: summative
sortorder: 3.9
appsused: indd
title: "Books Pinocchio"
level: cg6
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=192175&grpid=0&isprv=0&bp=0&ou=227660"
submission: "indd-book-package-plus-pdf"
links: |
  - Adobe: <a href="https://helpx.adobe.com/indesign/using/creating-book-files.html" title="Adobe: Help, Creating Books in InDesign" target="_blank">Creating Books</a>
  - <a href="bullet-and-number-lists.html" title="InDesign Bullet & Number Lists">About defined lists</a>
  - <a href="https://helpx.adobe.com/indesign/using/numbering-pages-chapters-sections.html" title="InDesign: Numbering Chapters" target="_blank">Numbering Chapters</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLCQ4NQ5PzDMzi9Vs8p8aUtG"
downloads: "https://www.dropbox.com/s/tmtvvpenmhfnwsd/indesign-books-pinocchio.zip?dl=1"
description: "In this assignment, you'll assemble the story of Pinocchio in an InDesign book which includes automatic numbering of pages & chapters, a table of contents, running headers, synchronized styles & swatches."
details:
assignment: |
  During class, you'll assemble the story of Pinocchio in a series of InDesign documents which will make up an InDesign book file. It will include a cover, front and end matter documents and the story content. All the features are:

  1. Automatic page numbers
  2. Custom colour swatches
  3. Paragraph styles
  4. Character Styles
  5. Defined number lists
  6. Chapter titles
  7. Running headers
  8. Table of contents

  Let's start setting this up.

  ### Create Book Documents

  Start by creating an InDesign document. This is the file which will serve as the master file from which all the other book files will be based. This is the format:

  <figure>
      <img class="size50" alt="new-document-setup" src="/images/indesign-books-pinocchio/new-document-setup.jpg">
  <figcaption>
    Create a single new InDesign document.
  </figcaption>
  </figure>

  We'll need to set up our master document before we duplicate it for each chapter. Remember, if you leave unwanted content in the panels in this document, it'll be present in all your book files. We don't want that. That's why it's important to plan ahead to build this document properly.

  ### Initial Document Setup

  #### Paragraph Styles

  Define the base serif in the Basic Paragraph style. Create a new style for the Base-Sans paragraph style. Create styles as shown below. Changing their appearance isn't that important for now.

  We're using <a href="https://fonts.adobe.com/fonts/adobe-caslon" title="Adobe Fonts: Adobe Caslon Pro" target="_blank">Adobe Caslon Pro</a> for body copy and <a href="https://fonts.adobe.com/fonts/futura-pt" title="Adobe Fonts: Futura PT" target="_blank">Futura PT</a> for titles. They're both on Adobe Fonts.

  <figure>
      <img class="size100" alt="styles-setup" src="/images/indesign-books-pinocchio/styles-setup.jpg">
  <figcaption>
    Change your Basic style, then add a Base Sans and a Body Copy style.
  </figcaption>
  </figure>

  For Futura, make sure you sync a bold instance. You'll need it for titles and the TOC later on.

  #### Clean out the Swatches panel

  We want to remove all un-needed swatches from the Swatches panel. Remember that book sync is non-destructive. It only adds content across documents, it doesn't remove any. That's why this needs to be done at the outset.

  Delete all unused colours. Let's add two colours to the panel.

  <figure>
      <img class="size100" alt="setup-colours" src="/images/indesign-books-pinocchio/setup-colours.jpg">
  <figcaption>
    We've added Pantone Cool Grey 10 in CMYK and Orange that's 60% magenta and 100% yellow.
  </figcaption>
  </figure>

  #### Layers

  Create layers for Folios, Images and Text. Make sure they're in that order. Folios underneath, then images, and text on top of everything.

  <figure>
      <img class="size33" alt="setup-layers-panel" src="/images/indesign-books-pinocchio/setup-layers-panel.jpg">
  <figcaption>
    Set up your layers like this.
  </figcaption>
  </figure>

  Remember, layers don't sync across documents unless you have content on them on master pages. When the master pages sync, the layers get created.

  #### Text Frames

  Create a primary text frame on your master pages. Make sure you have one on each master. Thread them together on the master. When you import your text in the next steps, hold the Shift key. That will make the text thread onto all the pages. Cool, eh?

  ### Book Documents

  Once your InDesign master document is ready with all the basic settings, we can duplicate it to have a total of seven files. See the image below.

  <div class="attentionbox shortcut">
    Close all InDesign documents. Go to the Finder, then hit cmd-D to duplicate the file until you have seven of them.
  </div>

  #### Cover, FM & EM

  Rename files for your Cover, Front Matter and End Matter files. Delete pages from the files to match the image below. Once all your InDesign documents are created, make a new Book file. Add the documents to the book file.

  <figure>
      <img class="size100" alt="setup-book-pages" src="/images/indesign-books-pinocchio/setup-book-pages.jpg">
  <figcaption>
    You have a cover, two EM & FM documents in addition to your main chapter documents, all in a book file.
  </figcaption>
  </figure>

  Now we have all our documents set up, it's time to add content to them. Remember to keep all book documents open <mark>except for the Cover and the End Matter file</mark>. We don't want them to sync the page numbers. They don't need them.

  Import each chapter's text into the appropriate InDesign document. Apply the Body Copy paragraph style to the text. Style the chapter numbers and chapter titles, too.


  ### Pagination

  #### Set Up Numbering

  Set up page numbering on the documents. There will be no page numbers on the cover document, obviously. We want lower case roman numerals for the Front Matter document, ie: i, ii, iii, iv, etc... There'll be regular arabic numerals for the chapter files of the document. ie: 1, 2, 3, 4, etc...

  <figure>
      <img class="size100" alt="setup-page-numbering" src="/images/indesign-books-pinocchio/setup-page-numbering.jpg">
  <figcaption>
    You can see the Book panel before and after page numbering has been adjusted.
  </figcaption>
  </figure>

  <div class="attentionbox achtung">
    Remember to turn on Master Page synching in the Book sync settings. Option-click on the Sync button to do so.
  </div>

  #### Folios

  Let's add page numbers to our master pages for the FM, EM and chapters. Make sure they're on the Folio layer and on the Master Page. Create a paragraph style for them.

  <figure>
      <img class="size100" alt="folios" src="/images/indesign-books-pinocchio/folios.jpg">
  <figcaption>
    Set up text variables in the footer from the chapter numbers and chapter titles.
  </figcaption>
  </figure>

  <div class="attentionbox shortcut">
    Shift-Tab creates a tab that alignes to the other end of the text frame. Use this in your folio text frame as shown.
  </div>

  ### Number List

  Let's make a number list across book files. Use the provided list of Pinocchio characters. You'll need to create a defined list in Paragraph Styles.

  <figure>
    <img class="size100" alt="number-list" src="/images/indesign-books-pinocchio/number-list.jpg">
  <figcaption>
    For the list to continue across book files, you need to give it a name in its paragraph style.
  </figcaption>
  </figure>

  If the numbers don't update in the second part of the list, make sure you update them from the Book panel's menu.

  ### Table of Contents

  Build a two-level table of contents in your Front Matter file for your document, including all the necessary paragraph styles.

  <figure>
      <img class="size100" alt="TOC" src="/images/indesign-books-pinocchio/toc.jpg">
  <figcaption>
    This is a two-level table of contents. Note that there are no page numbers on the first level entries.
  </figcaption>
  </figure>

  ### Cover Image

  To wrap things up, place the provided image on the cover.

  <img class="size75" alt="cover-image" src="/images/indesign-books-pinocchio/cover-image.jpg">

  Remember to make sure you image extends to the bleed line.

  ### Package Your Book.

  Save and close all of your book documents. Leave the Book panel open, and click the <span class="command">Save Book</span> button. Deselect all the documents in the Book panel. Go to the Book panel menu, then click on <span class="command">Package book for Print...</span>.

  <figure>
      <img class="size75" alt="package" src="/images/indesign-books-pinocchio/package.jpg">
  <figcaption>
    Use the Book panel's Package command to create a folder with all assets.
  </figcaption>
  </figure>

  Go back to your Book panel's menu. Use <span class="command">Export book to PDF</span> to create a PDF file of your book. This will be your second submission on Brightspace.

---
