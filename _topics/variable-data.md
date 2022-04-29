---
layout: submission
type: assignment
formsum: formative
sortorder: 4.0
appsused: ai
title: "Variable Data"
level: cg5
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=236853&grpid=0&isprv=0&bp=0&ou=279828"
submission: "my-assignment-folder"
links: |
  - Adobe: <a href="http://helpx.adobe.com/illustrator/using/data-driven-graphics-templates-variables.html" title="Adobe: Illustrator Variable Data" target="_blank">Variable Data</a>
downloads: "https://www.dropbox.com/s/wb89tvla7ox6t5u/illustrator-variable-data.zip?dl=1"
description: "Variable Data in Illustrator is a little-know feature that can save you hours of tedious, error-prone work. Using the Variables panel in Illustrator, you can easily create multiple variations of your artwork by merging a data source file (CSV or XML file) with an Illustrator document."
details: | 
  Using Variable Data in Illustrator will save you a lot of time and avoid entry errors. It allows you to re-use the same artwork with different data in it. A good example would be to output business cards for a company for hundreds of different individuals.

  ### Create a Workspace

  Before we get started, we'll create a Variable Data workspace in Illustrator.

  1. Type Shift-Tab to hide all of your panels.
  2. Open your Layers and your Variables panels.
  3. Save the workspace as *Variable Data*.

  #### Types of Variables

  <img class="size100" alt="illustrator-variable-types" src="/images/illustrator-variable-data/illustrator-variable-types.jpg">

  Objects such as point type, area type, vector art and placed images are containers for the data stored in the spreadsheet. They're simply place-holders which will be replaced by each row of data as the file is exported with our Batch Action.

  <img class="size100" alt="illustrator-variable-data" src="/images/illustrator-variable-data/illustrator-variable-data.jpg">

  ### Kinds of Variable Data

  #### Text Variables

  This type of variable looks to the spreadsheet's rows for text. As it progresses through the rows, it swaps out the text in the Illustrator document for each entry in the data. This is the most common type of variable. It can be point text or area text.

  The name of the Illustrator sub-layer for text needs to be named the same as the column in the .csv file.

  #### @ Linked Image Variables

  You can swap out placed/linked images based on the data in a spreadsheet. Illustrator will look at the path to an image in the .csv file, then cycle through all your images. The path to the image needs to look like this in your spreadsheet.

  <span class="command">/Users/Appleseed/Documents/Projects/Baseball-Cards/images/appleseed.jpg</span>

  The name of the Illustrator sub-layer for image needs to be named the same as the column in the .csv file. Add an @ symbol before the column name in the .csv file to indicate that this is an image variable.

  <figure>
      <img class="size100" alt="illustrator-variable-csv-file-photos" src="/images/illustrator-variable-data/illustrator-variable-csv-file-photos.jpg">
  <figcaption>
    Note the @ symbol for the Photo column in our .csv file.
  </figcaption>
  </figure>

  #### # Visibility Variables

  This is artwork we wish to reaveal or hide. Visibility is only On or Off. In your spreadsheet, that's expressed as TRUE or FALSE. Again, the header for a visibility variable is prefixed with a # symbol. This is how you show or hide objects on the artboard.

  <figure>
      <img class="size100" alt="illustrator-variable-csv-file-visibility" src="/images/illustrator-variable-data/illustrator-variable-csv-file-visibility.jpg">
  <figcaption>
    Note the # symbol for the visibility variable. Entries are TRUE or FALSE.
  </figcaption>
  </figure>

  The name of the Illustrator sub-layer for this content needs to be named the same as the column in the .csv file.

  #### % Graph Variables

  You need to create an Illustrator Graph to start. The graph data for each record must be saved in a text file. Each file contains the data from the Illustrator Graph Data panel. So you need to copy the data from that Illustrator panel into a spreadsheet. The data needs to be separated by tabs and not commas.

  We won't be dealing with graphs today for a lack of time. You can read more about adding graph variables at the provided Adobe support link.

  ### Editing Your Data

  We'll need a properly formatted spreadsheet in order to create the multiple files from our data. We'll set this up here.

  In our spreadsheet, columns are variables. Rows are the data sets which contain those variables. When showing the next data set in Illustrator, we're just moving to the next row in the spreadsheet. Each coloumn represents an object on your Artboard. Column heads cannot have spaces or special characters. They should be readable and descriptive.

  * An @ symbol before the column name represents an image.
  * The # symbol before the column name represents a visibility variable.
  * A % sign before the column name represents a graph.

  Go to the Google spreadsheet <a href="https://docs.google.com/spreadsheets/d/19S_r_LzZhPYa2Xv7GdzxFaW4qMRJ5APYc3mvnl8BMiU/edit?usp=sharing" title="Go to the Google Spreadsheet" target="_blank">from this link</a>.

  ### Important Notes

  <ul class="fs80">
    <li>The data field names in your spreadsheet should not contain blank spaces. For example, you can specify the data field as Company_Name instead of Company Name.</li>
    <li>Similarly, the paths referring to image and graph files should not contain any blank spaces. For example, the path of an image file should be <span class="command">/Users/Appleseed/Photos/BillTucker</span> instead of <span class="command">/Users/Appleseed/Photos/Bill Tucker</span>.</li>
    <li>All graph files linked from your data source file should be saved as comma-delimited (.csv) files.</li>
    <li>If you get an error message when you type the @ symbol at the beginning of the field, type an apostrophe (') before the @ symbol (such as '@Photos) to validate the function. Some applications, such as Microsoft Excel, reserve the @ symbol for functions.</li>
    <li>  The .csv file needs to be saved with RTF-8 encoding. Apple's Numbers app will do this automatically.</li>
  </ul>

  ### Layers → Columns

  We need to make sure that the Illustrator art is named the same as the column names in the data file.

  <figure>
      <img class="size100" alt="Illustrator-variables-column-names-layers" src="/images/illustrator-variable-data/Illustrator-variables-column-names-layers.jpg">
  <figcaption>
    As you can see, the names of the columns in the .csv file are the same as the sub-layer names in Illustrator.
  </figcaption>
  </figure>

  ### Hooking Up Your Data

  Now that we have a properly formatted data file in .csv format, we can connect it to our Illustrator document. Open the Illustrator file, then go <span class="command">Window > Variables</span> to get your Variables panel.

  <figure>
      <img class="size100" alt="Illustrator-variables-panels" src="/images/illustrator-variable-data/Illustrator-variables-panels.jpg">
  <figcaption>
    <ol>
    <li>Name sub-layers like column headings.</li>
    <li>Open the Variables panel.</li>
    <li>Import your .csv file.</li>
    <li>Link the variables to the objects on the page.</li>
    </ol>
  </figcaption>
  </figure>

  Click the <span class="command">Import</span> button in the panel. Choose your .csv file. The variables will appear in the panel. Now, we select objects on the artboard and click the appropriate buttons in the Variables panel to connect them.

  ### Preview Documents

  Now that the data is connected to artwork in Illustrator, we can preview the documents. In the Variables panel, choose a data set from the dropdown menu. You can now click the left and right arrows to cycle through all the entries in the csv file. The content should change with each entry and some artwork should show/hide, too.

  ### Exporting Data Sets

  We'll use an Illustrator action in a batch to export each record.

  1. Name a new action as 'Save Data Set as PDF'.
  1. Choose File > Save a Copy...
  1. Don't change the file name.
  1. Choose PDF as your file format.
  1. Choose PDF settings to suit your needs.
  1. Make sure 'View PDF after saving' is checked **off**.
  1. Click Save PDF
  1. Stop recording

   Now we'll use the Batch command to run the action on our data sets.

  1. Go to the Actions panel and choose *Batch...* from the flyout menu.
  1. In the 'Source' dropdown, choose 'Data Sets'.
  1. In 'Destination', choose 'None'. Choose a destination.
  1. For 'File Name', choose 'Data Set Name' as long as you know your data sets all have unique names.
   1. Finally, choose an error reporting option. Click 'OK'.

  <img class="size75" alt="illustrator-variable-PDF-files" src="/images/illustrator-variable-data/illustrator-variable-PDF-files.jpg">

   This batch process will save a series of PDF files where you tell it to. Voilà! You're done. Now you have the skills and knowledge to create dozens, if not hundreds of Illustrator files with variable content.

assignment: |

  As our formative assignment, let's create cards for each of the provided baseball players. Each card will have variable text, a photo for each, and some will have an All-Star graphic.

  We'll output the final cards as separate PDF files.
---

https://docs.google.com/a/algonquindesign.ca/spreadsheets/d/19S_r_LzZhPYa2Xv7GdzxFaW4qMRJ5APYc3mvnl8BMiU/edit?usp=sharing
