---
layout: submission
type: assignment
formsum: formative
sortorder: 4.0
appsused: indd
submission: "indesign-package"
title: "Our First Layout"
level: cg1
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=381847&grpid=0&isprv=0&bp=0&ou=409084"
links: |
  - <a href="https://helpx.adobe.com/indesign/using/create-documents.html" target="_blank" title="Adobe: Create Documents">Adobe: Create Documents</a>
  - <a href="https://helpx.adobe.com/indesign/using/threading-text.html" target="_blank" title="Adobe: Threading Text Frames">Adobe: Threading Text Frames</a>
  - <a href="https://helpx.adobe.com/indesign/using/creating-text-text-frames.html" target="_blank" title="Create Text Frames">Create Text Frames</a>
  - <a href="https://helpx.adobe.com/indesign/using/threading-text.html" target="_blank" title="Threading Text">Adobe: Threading Text</a>
  - <a href="https://helpx.adobe.com/indesign/using/text-wrap.html" target="_blank" title="Adobe: Text Wrap">Adobe: Text Wrap</a>
  - <a href="https://helpx.adobe.com/indesign/using/formatting-text.html#use_quick_apply" target="_blank">Adobe: Quick Apply</a>
video: "https://www.youtube.com/embed/videoseries?list=PL4qBMvigUSLDjkXfBZub8komrk3Bj3RyO"
downloads: "https://www.dropbox.com/s/sgcn06ce93yzpl9/indesign-our-first-layout.zip?dl=1"
description: "In our introduction to page layout in InDesign, we'll build a single-page layout promoting Apple's Mac Mini desktop computer. We'll build this as a template so that it's easy to update for future products."
details: |
  This is going to be our first foray into page layout in InDesign. We'll build a single-page sell sheet for Apple's Mac Mini. The goal here is to build it as a bit of template, so we can swap out the content for a different product in the future. All the tools below help us create this layout with that goal in mind.

  ### Using Fonts

  This document uses two typefaces: Acumin Variable Concept and Minion Variable Concept.

  <img class="size100" alt="Acumin and Minion Fonts" src="/images/indesign-our-first-layout/indesign-fonts-acumin-minion.svg">

  Acumin is a <a href="https://en.wikipedia.org/wiki/Sans-serif#Neo-grotesque" title="What is a neo-grotesque sans serif font?" target="_blank">neo-grotesque sans-serif</a> typeface. It's best used for headlines. Minion is a serif typeface. It's great for body copy. This is a good general rule: sans-serif fonts for titles and serif fonts for long lengths of text.

  This is an explanation of point, picas and inches.

  <img class="size50 center" alt="Units of measure Point, Picas and Inches" src="/images/svg/picas-points-and-inches.svg">


  ### The What, Why & How of Style Sheets

  Style sheets allow you to store the appearance settings of text in a central location called either a paragraph style or a character style.

  The greatest benefit of style sheets is that you can change their settings, then all the text that has that style applied changes automatically. The beauty of this is the speed that changes can be made. Also, the lack of manual, one-off edits makes for fewer user errors and omissions.

  #### Paragraph Vs. Character Styles

  Paragraph Styles are so-called because they only apply to whole paragraphs of text. You cannot make one word *italic* with a Paragraph Style. That's what Character Styles are for.

  The rule for deciding which to use is to default to Paragraph Styles until they can't do what you want them to. Never use Character Styles unless you're styling letters *within* a paragraph. Otherwise, forget they exist.

  Character Styles are only used to <span style="color: red;">style</span> elements <span style="color: red;">within</span> a block, not the whole block itself.

  <figure>
      <img class="size100" alt="indesign-character-styles" src="/images/indesign-our-first-layout/indesign-character-styles.jpg">
  <figcaption>
  Character styles are for styling characters within a paragraph and not the whole paragraph.    
  </figcaption>
  </figure>


  Character styles are most often used from within paragraph styles. These are called nested styles. Character styles may be nested in different ways. There are InDesign's actual Nested Styles, there are Grep Styles and others. We use these because applying Character Styles manually is very tedious.

  ### Paragraph Styles

  #### What is a Paragraph?

  Most of the work we need to do to create this layout is simply creating paragraph styles, then applying them to the text.

  <figure>
      <img class="size75 borderlightgrey1" alt="what-is-a-paragraph-to-indesign" src="/images/indesign-our-first-layout/indesign-what-is-a-paragraph.jpg">
  <figcaption>
  Every time you see the pilcrow character, you're ending a paragraph.    
  </figcaption>
  </figure>

  Paragraph styles can only style whatever is between to Pilcrow <span class="">&#182;</span> characters.

  To InDesign, what follows is a paragraph.<span class="">&#182;</span>

  <span class="">Z&#182;</span>

  The letter Z above is a paragraph, according to InDesign, because there's a Pilcrow before and after it.

  ### Setting Base Styles

  Formatting text in InDesign can either be a headache or a pleasure. We'll give you the tools you need to make styling text quick and error-free.

  Before we can start formatting the document text, we need to create a few *base* paragraph styles.

  #### Edit Basic Paragraph

    <figure>
    <img alt="indesign-paragraph-styles-dialogue" src="/images/indesign-style-sheets/indesign-paragraph-styles-dialogue.jpg" class="size100">
  <figcaption>
  Create paragraph styles based on other paragraph styles.    
  </figcaption>
  </figure>


  In all InDesign documents, there's a Basic Paragraph Style. It's the default stylesheet that applies to all text as it's brought into InDesign. It's a good idea to change its font and size to the size of your planned Body Copy style.

  Paragraph Styles inherit properties from parent paragraph styles. We're going to create underlying serif and sans-serif styles. Each will have only minimal styling, including the font selection and not much else. The base serif style is the Basic Paragraph Style. We'll create a new stylesheet for the *Base Sans*.

  <figure>
      <img alt="paragraph-styles-panel-based-on" src="/images/indesign-our-first-layout/paragraph-styles-panel-based-on.jpg" class="size33">
  <figcaption>
    All the styles are based on Basic in this case.
  </figcaption>
  </figure>


  This makes it that you can change a font across a whole document by changing only this one stylesheet. As an example. If all of your titles are styled in Acumin. 

  You'll base all of your sans-serif styles on your *Base Sans*. If your client (or your teacher) then asks you to change all titles to a different font, you only need to change the *Base Sans*. Because all others have it as a parent, they'll all change.

  Make the most of this inheritance property for style sheets.

  #### Size and Leading

  In your Paragraph Styles, you can define the size of the text and its leading. These settings are found in *Basic Character Formats* in your stylesheet's settings. If you're just starting out, it's a good idea to leave the leading to *Auto*. This establishes a 120% value. So 10 point type will have a 12 point leading.

    <figure>
    <img alt="indesign-simple-paragraph-style-example" class="size100 borderlightgrey1" src="/images/indesign-our-first-layout/indesign-new-paragraph-style.jpg">
  <figcaption>
  These are some settings for a new paragraph style.    
  </figcaption>
  </figure>

  #### Paragraph Spacing

  When reading text, it's ideal to have a visual indication of the end of a paragraph and the start of the next. This is either achieved with a first line indent or a space after the paragraph — never both.

    <figure>
    <img class="size100 borderlightgrey1" alt="indesign-paragraph-spacing" src="/images/indesign-our-first-layout/indesign-paragraph-spacing.jpg">
  <figcaption>
  To indicate a new paragraph, either use a first line indent or a space after — never both.    
  </figcaption>
  </figure>


  You can see an example of a first line indent on the left of the above image. On the right, there's a space after the paragraph. Choose one of the two treatments, not both. In this specific case, we'll create space after paragraphs in our style sheet.

  #### Text Colour

  In some instances, you want to change the colour of your text. You can do this in a stylesheet, along with all the other properties. It's found under the *Character Colour* pane in your stylesheets settings.

    <figure>
    <img alt="indesign-paragraph-style-character-colour" class="size100" src="/images/indesign-style-sheets/indesign-paragraph-style-character-colour.jpg">
  <figcaption>
    This is where you change the colour of your text in a paragraph style.
  </figcaption>
  </figure>

  There are many, many more properties in the Paragraph Styles Options dialogue. We'll explore most of them over time.

  ### Columns of Text

  When creating columns of text, always create multi-column text frames. Never create multiple separate text frames side-by-side. The main text of our whole layout is in one three-column text frame.

    <figure>
    <img class="size100" alt="indesign-column-break" src="/images/indesign-our-first-layout/indesign-column-break.jpg">
  <figcaption>
  Create column breaks by typing the Return character.  
  </figcaption>
  </figure>

  The proper method to get text to jump to the next column is to insert a column break. You can do this with a right-click or by typing <span class="command">Enter</span>, not <span class="command">Return</span>.

  Make sure you delete every last character at the end of the paragraph the <span class="orange fw800">&#8744;</span> glyph needs to be the last glyph in the column, right after the period glyph.

  ### Parent Pages

  In publications, some elements repeat themselves on multiple pages. Rather than manually placing items on each page of your document, we place them on parent pages.

  <img class="size33" alt="pages-panel" src="/images/indesign-our-first-layout/indesign-pages-panel.jpg">

  You can see, in the image above, that the black bar with the  logo is on the Parent Page. You can also see the letter A at the top of the document page. That means A-Parent is applied to the document page. Anything on A-Parent will appear on page one.

  ### Bleeds

  The bleed area is the narrow space all around the exterior of the pages ending at the red line. It's extra space to prevent unsightly white area in case of inaccurate cutting by the printer. It's generally one eighth of an inch. That's 0.125" or 9 points.

    <figure>
    <img class="size100 borderlightgrey1" alt="indesign-bleeds" src="/images/indesign-our-first-layout/indesign-bleeds.jpg">
  <figcaption>
  If content touches the edge of the page, you need to extend it to the bleed line. Be precise with positioning at the bleed. Go no further.
  </figcaption>
  </figure>

  ### Placing Images

  In Adobe-speak, importing an image is called *placing*. We'll place the image of the Mac Mini on the page. When you place an image, it's always inside a frame.

  <img class="size100" alt="indesign-image-frame" src="/images/indesign-our-first-layout/indesign-image-frame.jpg">

  In the image above, the photo has a brown frame around it. That's our Photoshop file. The blue box is the InDesign frame. <a href="raster-image-fundamentals.html" title="See more about placing images here">See more about placing images here</a>.

  ### Preflight & Package

  The nature of an InDesign document is that it depends on certain files being present on your computer or online. These inlclude photos, graphics and fonts. If these aren't present, the document won't display properly. An image may not appear at all. A font may be substituted for another, changing the look of your design.

  #### Font Usage

  Once you're done your layout, you want to double-check that your font and image usage is correct. Let's check fonts first. Go <span class="command">Type > Find Font...</span>. A dialogue opens which shows you which fonts have been used in your document.

    <figure>
    <img class="size50" alt="find-font-dialogue" src="/images/indesign-our-first-layout/indesign-find-font-dialogue.jpg">
  <figcaption>
  This is the Find Font dialogue. It tells you which fonts are in use in your document. 
  </figcaption>
  </figure>

  You can see in the Find Font dialogue that we only have the fonts we've actually used in our document.

  #### Image Usage

  We need to ensure that the images we've place in our document are properly linked to our file. To do so, we can check our Links panel. Go <span class="command">Window > Links</span>. This panel has a list of each object we've placed on our pages. It also displays the properties of those images and graphics.

    <figure>
    <img class="size33" alt="links-panel" src="/images/indesign-our-first-layout/indesign-links-panel.jpg">
  <figcaption>
  This is InDesign's Links panel.
  </figcaption>
  </figure>

  If there's a problem with an image, there will either be a question mark or an exclamation mark next to it in the Links Panel. A qestion mark means that the image has been edited since you placed it in InDesign. An exclamation mark means InDesign doesn't know where the image is on our computer.

  ### Packaging

  The Package command is under <span class="command">File > Package...</span>. The packaging process gathers all files related to an InDesign document, then *copies* them into a new folder. This folder has your self-contained project in it, which you an hand off to a printer for production.

    <figure>
    <img class="size100 borderlightgrey1" alt="indesign-package-folder" src="/images/indesign-our-first-layout/indesign-package-folder.jpg">
  <figcaption>
  This folder is the result of the packaging process in InDesign.    
  </figcaption>
  </figure>

  The package folder includes your InDesign document with all its support files — images and fonts. It can include a PDF of layout. You can also produce an IDML file which is your layout file, openable in older versions of InDesign.

  The package folder automatically gets named with the document name. The whole folder is what you need to zip-compress to submit.

  <div class="attentionbox achtung">
    Handing in an InDesign document alone is completely useless and unusable. Doing so is handing in an incomplete project. You will earn a grade of 0 (F).
  </div>

  To compress the folder, right-click on it, then choose <span class="command">Compress...</span> Submit that zip file.

assignment: |
  This is what our final layout is going to look like. Note how everything in the layout lines up with grid we've established in the document setup.

    <figure>
    <img class="size75" alt="indesign-mac-mini-sell-sheet" src="/images/indesign-our-first-layout/indesign-mac-mini-sell-sheet.jpg">
  <figcaption>
    This is what the completed layout looks like.
  </figcaption>
  </figure>


  Go <span class="command">File > New</span> in InDesign. We'll create a single-page document with:
  * No facing pages
  * 3 columns
  * 0p9 point gutters
  * 2p0 point margins
  * 0p9 point bleeds

  #### Type Specimen

  We'll be using Acumin Variable Concept and Minion Pro Variable Concept in this layout.

    <figure>
    <img src="/images/indesign-our-first-layout/type-specimen.jpg" class="size75 borderlightgrey1" alt="type-specimen">
  <figcaption>
    This is a type specimen for the document.
  </figcaption>
  </figure>


  #### Save the File

  Let's save our InDesign document as:

  <div class="filename">appleseed-johnny-#-our-first-layout.indd</div>
  
  into the folder you downloaded.

---
