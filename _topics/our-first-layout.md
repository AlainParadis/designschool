---
layout: submission
type: card
formsum: formative
sortorder: 3.3
appsused: indd
submission: indesign-package
title: "Our First Layout"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=84505&grpid=0&isprv=0&bp=0&ou=92671"
links: |
  - <a href="https://helpx.adobe.com/indesign/using/create-documents.html" target="_blank" title="Adobe: Create Documents">Adobe: Create Documents</a>
  - <a href="https://helpx.adobe.com/indesign/using/threading-text.html" target="_blank" title="Adobe: Threading Text Frames">Adobe: Threading Text Frames</a>
  - <a href="https://helpx.adobe.com/indesign/using/creating-text-text-frames.html" target="_blank" title="Create Text Frames">Create Text Frames</a>
  - <a href="https://helpx.adobe.com/indesign/using/threading-text.html" target="_blank" title="Threading Text">Adobe: Threading Text</a>
  - <a href="https://helpx.adobe.com/indesign/using/text-wrap.html" target="_blank" title="Adobe: Text Wrap">Adobe: Text Wrap</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLDjkXfBZub8komrk3Bj3RyO"
downloads: "https://www.dropbox.com/s/9ymsw3yk3qkmayf/indesign-our-first-layout.zip?dl=1"
description: "In our introduction to page layout in InDesign, we'll build a single page layout promoting Apple's Mac Mini desktop computer."
details: |
  This is what our final layout is going to look like. Note how everything in the layout lines up with grid we've established in the document setup.

  <img class="size75 center" alt="indesign-mac-mini-sell-sheet" src="/images/indesign-our-first-layout/indesign-mac-mini-sell-sheet.jpg">

  Go <span class="command">File > New</span> in InDesign. We'll create a single-page document with:

  * No facing pages
  * 3 columns
  * 9 point gutters (0p9)
  * 21 point margins (1p9)
  * 9 point bleeds (0p9)

  This is an explanation of point, picas and inches.

  <img class="size50 center" alt="Units of measure Point, Picas and Inches" src="/images/svg/picas-points-and-inches.svg">

  ## Using Fonts

  This document uses two typefaces: Myriad Pro for titles and Minion Pro for body copy.

  <img class="size100" alt="Myriad and Minion Fonts" src="/images/indesign-our-first-layout/indesign-fonts-myriad-minion.svg">

  Myriad Pro is a *sans-serif* typeface. It's best used for headlines. Minion Pro is a *serif* typeface. It's great for body copy. This is a good general rule: sans-serif fonts for titles and serif fonts for long lengths of text.

  We need to activate these two fonts on the <a href="https://fonts.adobe.com/" target="_blank" title="Adobe Fonts web site">Adobe Fonts web site</a>. You'll need to be logged in with your Adobe ID.

  ## The What, Why & How of Style Sheets

  Style sheets allow you to store the appearance settings of text in a central location called either a paragraph style or a character style.

  The greatest benefit of style sheets is that you can change their settings, then all the text that has that style applied changes automatically. The beauty of this is the speed that changes can be made. Also, the lack of manual, one-off edits makes for fewer user-errors and omissions.

  ### Paragraph Vs. Character Styles

  Paragraph Styles are so called because they only apply to whole paragraphs of text. You cannot make one word *italic* with a Paragraph Style. That's what Character Styles are for.

  The rule for deciding which to use is to default to Paragraph Styles until they can't do what you want them to. Never use Character Styles unless you're styling letters *within* a paragraph. Otherwise, forget they exist.

  Character Styles are only used to <span style="color: red;">style</span> elements <span style="color: red;">within</span> a block, not the whole block itself.

  <img class="size100" alt="indesign-character-styles" src="/images/indesign-our-first-layout/indesign-character-styles.jpg">

  Character styles are most often used from within paragraph styles. These are called nested styles. Character styles may be nested in different ways. There are InDesign's actual Nested Styles, there are Grep Styles and others. We use these because applying Character Styles manually is very tedious.

  ## Paragraph Style Sheets

  ### What is a Paragraph?

  Most of the work we need to do to create this layout is simply creating paragraph styles, then applying them to the text.

  <img class="size75" alt="what-is-a-paragraph-to-indesign" src="/images/indesign-our-first-layout/indesign-what-is-a-paragraph.jpg">

  Paragraph styles can only style whatever is between to Pilcrow <span class="fw600">&#182;</span> characters.

  To InDesign, what follows is a paragraph.<span class="fw600">&#182;</span>

  <span class="fw600">Z&#182;</span>

  The letter Z above is a paragraph, according to InDesign, because there's a Pilcrow before and after it.

  ## Setting Base Styles

  Formatting text in InDesign can either be a headache or a pleasure. We'll give you the tools you need to make styling text quick and error-free.

  Before we can start formatting the document text, we need to create a few *base* paragraph styles.

  ### Edit Basic Paragraph

  <img alt="indesign-paragraph-styles-dialogue" src="/images/indesign-style-sheets/indesign-paragraph-styles-dialogue.jpg" class="size100">

  In all InDesign documents, there's a Basic Paragraph Style. It's the default stylesheet that applies to all text as it's brought into InDesign. It's a good idea to change its font and size to the size of your planned Body Copy style.

  Paragraph Styles inherit properties from parent paragraph styles. We're going to create underlying serif and sans-serif styles. Each will have only minimal styling, including the font selection and not much else. The base serif style is the Basic Paragraph Style. We'll create a new stylesheet for the *Base Sans*.

  <img alt="paragraph-styles-panel-based-on" src="/images/indesign-our-first-layout/paragraph-styles-panel-based-on.jpg" class="size33">

  This makes it that you can change a font across a whole document by changing only this one stylesheet. As an example. If all of your titles are styled in Myriad Pro. 

  You'll base all of your sans-serif styles on your *Base Sans*. If your client (or your teacher) then asks you to change all titles to a different font, you only need to change the *Base Sans*. Because all others have it as a parent, they'll all change.

  Make the most of this inheritance property for style sheets.

  ### Size and Leading

  In your Paragraph Styles, you can define the size of the text and its leading. These settings are found in *Basic Character Formats* in your stylesheet's settings. If you're just starting out, it's a good idea to leave the leading to *Auto*. This establishes a 120% value. So 10 point type will have a 12 point leading.

  <img alt="indesign-simple-paragraph-style-example" class="size100" src="/images/indesign-style-sheets/indesign-simple-paragraph-style-example.jpg">

  ### Paragraph Spacing

  When reading text, it's ideal to have a visual indication of the end of a paragraph and the start of the next. This is either achieved with a first line indent or a space after the paragraph — never both.

  <img class="size100" alt="indesign-paragraph-spacing" src="/images/indesign-our-first-layout/indesign-paragraph-spacing.jpg">

  You can see an example of a first line indent on the left of the above image. On the right, there's a space after the paragraph. Choose one of the two treatments, not both. In this specific case, we'll create space after paragraphs in our style sheet.

  ### Text Colour

  In some instances, you want to change the colour of your text. You can do this in a stylesheet, along with all the other properties. It's found under the *Character Colour* pane in your stylesheets settings.

  <img alt="indesign-paragraph-style-character-colour" class="size100" src="/images/indesign-style-sheets/indesign-paragraph-style-character-colour.jpg">

  There are many, many more properties in the Paragraph Styles Options dialogue. We'll explore most of them over time.

  ## Columns of Text

  The main text of our whole layout is in one three-column text frame.

  <img class="size100" alt="indesign-column-break" src="/images/indesign-our-first-layout/indesign-column-break.jpg">

  The proper method to get text to jump to the next column is to insert a column break. You can do this with a right-click or by typing <span class="command">Enter</span>, not <span class="command">Return</span>.

  Make sure you delete every last character at the end of the paragraph the <span style="color: #0096FF;">&#8744;</span> glyph needs to be the last glyph in the column, right after the period glyph.

  ## Master Pages

  In publications, some elements repeat themselves on multiple pages. Rather than manually placing items on each page of your document, we place them on master pages.

  <img class="size33" alt="pages-panel" src="/images/indesign-our-first-layout/indesign-pages-panel.jpg">

  You can see, in the image above, that the black bar with the  logo is on the Master Page. You can also see the letter A at the top of the document page. That means A-Master is applied to the document page. Anything on A-Master will appear on page one.

  ## Bleeds

  The bleed area is the narrow space all around the exterior of the pages ending at the red line. It's extra space to prevent unsightly white area in case of inaccurate cutting by the printer. It's generally one eighth of an inch. That's 0.125" or 9 points.

  <img class="size100" alt="indesign-bleeds" src="/images/indesign-our-first-layout/indesign-bleeds.jpg">

  If content touches the edge of the page, you need to extend it to the bleed line. Be precise with positioning at the bleed. Go no further.

  ## Placing Images

  In Adobe-speak, importing an image is called *placing*. We'll place the image of the Mac Mini on the page. When you place an image, it's always inside a frame.

  <img class="size100" alt="indesign-image-frame" src="/images/indesign-our-first-layout/indesign-image-frame.jpg">

  In the image above, the photo has a brown frame around it. That's our Photoshop file. The blue box is the InDesign frame. <a href="raster-image-fundamentals.html" title="See more about placing images here">See more about placing images here</a>.

  ## Preflight & Package

  The nature of an InDesign document is that it depends on certain files being present on your computer or online. These inlclude photos, graphics and fonts. If these aren't present, the document won't display properly. An image may not appear at all. A font may be substituted for another, changing the look of your design.

  ### Font Usage

  Once you're done your layout, you want to double-check that your font and image usage is correct. Let's check fonts first. Go <span class="command">Type > Find Font...</span>. A dialogue opens which shows you which fonts have been used in your document.

  <img class="size50" alt="find-font-dialogue" src="/images/indesign-our-first-layout/indesign-find-font-dialogue.jpg">

  You can see in the Find Font dialogue that we only have the font we've actually used in our document.

  ### Image Usage

  We need to ensure that the images we've place in our document are properly linked to our file. To do so, we can check our Links panel. Go <span class="command">Window > Links</span>. This panel has a list of each object we've placed on our pages. It also displays the properties of those images and graphics.

  <img class="size33" alt="links-panel" src="/images/indesign-our-first-layout/indesign-links-panel.jpg">

  If there's a problem with an image, there will either be a question mark or an exclamation mark next to it in the Links Panel. A qestion mark means that the image has been edited since you placed it in InDesign. An exclamation mark means InDesign doesn't know where the image is on our computer.

  ### Packaging

  The Package command is under <span class="command">File > Package...</span>. The packaging process gathers all files related to an InDesign document, then copies them into a new folder. This folder has your self-contained project in it, which you an hand off to a printer for production.

  <img class="size100" alt="indesign-package-folder" src="/images/indesign-our-first-layout/indesign-package-folder.jpg">

  The package folder includes your InDesign document with all its support files — images and fonts. It can include a PDF of layout. You can also produce an IDML file which is your layout file, openable in older versions of InDesign.

  The package folder automatically gets named with the document name. The whole folder is what you need to zip-compress to submit.

  <div class="attentionbox achtung">
    Handing in an InDesign document alone is completely useless and unusable. Doing so is handing in an incomplete project. You will earn a grade of 0 (F).
  </div>

  To compress the folder, right-click on it, then choose <span class="command">Compress...</span> Submit that zip file.

assignment: |
  Your summative InDesign assignment is <a href="vw-layout.html" title="Your summative InDesign assignment." target="_blank">on the next page</a>.
---
