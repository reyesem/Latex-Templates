# LaTeX Templates

These are templates for common documents (presentations, letters, posters, course notes) I work with as a professor.  The color schemes have been chosen to adhere to the Branding Guidelines of Rose-Hulman Institute of Technology.

All the files needed to produce a working document are included in the repository.  Note that ethical reasons, institute-specific files (such as official logo, letterhead, etc.) have been removed; in their place are generic images.  Contact your organization for versions of these files suitable for your purposes.


## Slide Presentations
Slides are similar to the Madrid theme that is built-in to Beamer.  Default options specify a clean presentation with few elements.  Files for presentations include:

  - __beamerthemeRHITslides.sty__: This style file is necessary for implementing the color scheme of RHIT and defining the layout as well as key macros.  This can be placed in the root directory with other style files or simply included in the same folder as your presentation.  In general, you should not need to make changes in this file.  If you do, consult the [Beamer User Guide](http://ctan.math.utah.edu/ctan/tex-archive/macros/latex/contrib/beamer/doc/beameruserguide.pdf).
  - __RHIT_logo.png__: This is the logo for RHIT that has the full name of the univeristy.
  - __RHITBeamer.tex__: Template presentation.  This file is what you should directly alter for creating your presentation.  The file includes documentation for making any necessary changes and provides examples of different components.
  

## Poster Presentations
Provides a simple 3-column poster suitable for electronic or physical poster presentations.  Files for poster include:

  - __beamerthemeRHITposter.sty__: This style file is necessary for implementing the color scheme of RHIT and defining the layout as well as key macros.  This can be placed in the root directory with other style files or simply included in the same folder as your presentation.  In general, you should not need to make changes in this file.  If you do, consult the [Beamer User Guide](http://ctan.math.utah.edu/ctan/tex-archive/macros/latex/contrib/beamer/doc/beameruserguide.pdf).
  - __RHIT_logo.png__: This is the logo for RHIT that has the full name of the univeristy.
  - __RHITposter.tex__: Template poster.  This file is what you should directly alter for creating your presentation.  The file includes documentation for making any necessary changes and provides examples of different components.
  
  
## Letterhead
Essentially, this takes a general letter set-up within LaTeX and overlays a portion of the official letterhead in the background.  The dimensions are set to make the most of the page.  Files for letterhead include:

  - __RHITletter.sty__: This style file is necessary for implementing the color scheme of RHIT and defining the layout as well as key macros.  This can be placed in the root directory with other style files or simply included in the same folder as your presentation.  In general, you should not need to make changes in this file.
  - __RHIT_header.pdf__: This is the top portion of the letterhead to place in the background of the page.
  - __RHITposter.tex__: Template letterhead.  This file is what you should directly alter for creating your letter.  The file includes documentation for making any necessary changes and provides examples of different components.
