---
layout: submission
type: assignment
formsum: formative
sortorder: 1.3
appsused: psd
title: "Blend Modes"
level: cg2
brightspace: "https://brightspace.algonquincollege.com/d2l/lms/dropbox/user/folder_submit_files.d2l?db=289093&grpid=0&isprv=0&bp=0&ou=314364"
submission: "my-assignment-folder"
links: |
  - Adobe: <a href="https://helpx.adobe.com/photoshop/using/blending-modes.html" target="_blank" title="Blending Modes">Blending Modes</a>
video:
downloads: "https://www.dropbox.com/s/ufziabhdlq7tl4c/photoshop-blend-modes.zip?dl=1"
description: "Blend Modes are used like paints being mixed. You have your base colour which you blend to obtain your blended result."
details: |
  Believe it or not, Photoshop blend modes are pretty cool. Just take a look at this.

  <figure>
      <img class="size100" alt="photoshop-blend-modes-turn-on-lights" src="/images/photoshop-blend-modes/photoshop-blend-modes-turn-on-lights.gif">
  <figcaption>
    Open the 01-turn-on-the-lights.psd file. Set the Blend Mode of the top layer to Lighten.
  </figcaption>
  </figure>

  ### Important Keyboard Shortcuts

  These keyboard shortcuts should be committed to memory. They'll help you with this assignment and all the rest of your Photoshop work, especially when you're working with layer masks.

  D: Set foreground & background swatches to default colours, black & white.

  X: Switch focus of foreground/background colours.

  ⌘-Delete: Fill with background colour.

  Option-Delete: Fill with foreground colour.

  B: Brush Tool. Right-click with Brush tool for controls.

  [ &nbsp;  or &nbsp; ] : Make brush smaller or bigger.

  ### Blending Basics

  #### Opacity

  Opacity is the most basic type of blending. If you reduce the opacity of a layer, it blends with the layer(s) below.

  <figure>
      <img class="size33" alt="photoshop-opacity-shortcuts" src="/images/photoshop-blend-modes/photoshop-opacity-shortcuts.gif">
  <figcaption>
    Change the opacity of a layer by typing a number. 5 equals 50%. 55 equals 55% opacity.
  </figcaption>
  </figure>

  #### Blend Modes

  You'll find, as you navigate through Photoshop, you'll encounter Blend Modes menues everywhere. As you create new layers, there's an option to choose a blend mode. There are blend modes for individual painting tools, too. They're everywhere.

  The modes available from the Blend Modes menu determine how a layer blends with a layer below. The painting tools also have their own blend modes. That means that you can paint on a layer with a tool in a certain blend mode, while the current layer can have a different blend mode.

  <div class="attentionbox shortcut">
    While you have the Move Tool active, you can use Shift with + or - to cycle through the Blend Modes menu.
  </div>

  There are three blend modes that you really need to know:

  Screen
  : Ignores black. Light pixels get lighter. It's like aiming two projectors at the same spot. The dark pixels cancel each other out. The lighter pixels get lighter.

  Multiply
  : Ignores white. It makes things darker. It's like stacking two coloured transparencies on top of each other. The darks get darker.

  Overlay
  : It ignores grey. This is a combination fo Screen and Multiply. It increases contrast.

  <figure>
      <img class="size100" alt="photoshop-blend-modes-explainer" src="/images/photoshop-blend-modes/photoshop-blend-modes-explainer.svg">
  <figcaption>
    This is a quick Blend Modes explainer. It covers the essentials.
  </figcaption>
  </figure>

  Open the provided file. Test switching the blend modes for each of the grey, black or white bars. This will help you understand the main categories of blend modes.

  You can make tonal adjustments in a non-destructive workflow by using blend modes. Let's fix a photo using this technique.

  <figure>
      <img class="size100" alt="tonal-corrections-with-blend-modes" src="/images/photoshop-blend-modes/tonal-corrections-with-blend-modes.jpg">
  <figcaption>
    In this photo, we've used the Screen blend mode to lighten areas of the photo.
  </figcaption>
  </figure>

  All we need to do to lighten the dark leaves is to duplicate the original layer. Set its blend mode to <span class="command">Screen</span>. Mask out the parts of the photo you don't want to be lightened.

  To darken over-exposed areas, duplicate the original layer again. Set the new layer to <span class="command">Multiply</span>. Mask out the area of the photo you don't want darkened.

  #### Lens Flare

  We can use blend modes to make the most of the lens flare filter.

  <figure>
      <img class="size100" alt="photoshop-lens-flare" src="/images/photoshop-blend-modes/photoshop-lens-flare.jpg">
  <figcaption>
    Blend modes can assist in using filters like Lens Flare.
  </figcaption>
  </figure>
  Create a new layer above your photo. Fill it with black by hitting D, then <span class="command">Option-Delete</span>. Use <span class="command">Filter > Render Lens Flare...</span>. Change the blend mode of the black layer to <span class="command">Screen</span>.

  #### Sharpening

  You can even use a blend mode to sharpen a blurry photo. Sharpening with this method is a non-destructive and subtle way to apply sharpening.

  <figure>
      <img class="size100" alt="photoshop-sharpen-with-high-pass" src="/images/photoshop-blend-modes/photoshop-sharpen-with-high-pass.jpg">
  <figcaption>
    See the difference between the left and the right sides of this photo? It's subtle sharpening.
  </figcaption>
  </figure>

  1. Duplicate the layer you want to sharpen with <span class="command">Option-Command-J</span>.
  2. Name the new layer. Right-click on the new layer, then choose <span class="command">Convert to Smart Object</span>.
  3. Now use <span class="command">Filter > Other > High Pass...</span>.
  4. Set the number as high as you can without showing colour through the grey.
  5. Change the grey layer's blend mode to <span class="command">Overlay</span>.

  If you need to sharpen more or less, simply double-click on the High Pass entry in the Layers panel to edit its value.

  <div class="attentionbox tip">
    Let's set up an automated workflow so we don't forget these steps in the future.
  </div>

  #### Softening

  Now, allow me to blow your mind further. You can use the same technique to create the opposite effect. Rather than sharpening, you can smooth/blur areas very gently.

  <figure>
      <img class="size100" alt="photoshop-smooth-skin-with-high-pass" src="/images/photoshop-blend-modes/photoshop-smooth-skin-with-high-pass.jpg">
  <figcaption>
    Invert the grey layer to create a subtle smoothing effect.
  </figcaption>
  </figure>

  All you need to do is invert the grey layer with <span class="command">⌘-i</span>. This will have a smoothing effect. All you need to do is mask areas you don't want smoothed.

  ### Blend If

  Blend If functionality is accessed in a layer's blending options. You can access this from the *fx* button at the bottom of the Layers panel or by double-clicking on a layer's icon. At the bottom of the Blending Options dialogue, you'll see the the Blend If controls.

  <figure>
      <img class="size100" alt="photoshop-blend-if-replace-sky" src="/images/photoshop-blend-modes/photoshop-blend-if-replace-sky.jpg">
  <figcaption>
    Use Blend If to reveal the sky on the layer below.
  </figcaption>
  </figure>

assignment: |
  Use blend modes in the provided photos to execute each of the tasks described above.

  01-photoshop-tonal-corrections-with-blend-modes.psd
  : Lighten the foreground and darken the background using blend modes (and masks).

  02-photoshop-lens-flare.psd
  : Create a lens flare where the sun is shining behind the man.

  03-photoshop-sharpen-with-high-pass.psd
  : Use the sharpen with High Pass method to gently sharpen the photo of chipmunks.

  04-photoshop-smooth-skin-with-high-pass.psd
  : Use the High Pass technique to smooth the woman's skin.

  05-photoshop-blend-if-full-moon.psd
  : Use Blend If to blend the black around the moon. Also, make the moon appear as though it's behind the grass using Blend If.
---
 