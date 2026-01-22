# html-resume

## Fonts, Icon Fonts, and Dependencies

* [Open Sans](https://www.google.com/fonts/specimen/Open+Sans), [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro) and [Source Sans Pro](https://www.google.com/fonts/specimen/Source+Sans+Pro) are used at various weights, but are not included in this repository. Please follow the links to download the fonts onto your computer.
* Icons from [Font Awesome](https://fortawesome.github.io/Font-Awesome/) are used and are incorporated as a git submodule in this repository.
* [Normalize.css](https://necolas.github.io/normalize.css/) is used and is incorporated as a git submodule in this repository.

## Rendering the PDF

* Just open the HTML file with the browser. No need to serve the document from any kind of web server --- the ``file:///`` protocol should be good enough.
* On Firefox:
  * You probably need to remove any page margins in **about:config**.
  * Uncheck **Ignore Scaling and Shrink To Fit Page Width**.
  * Check **Print Background Colors**.
  * Clear out the headers and footers.
  * Save as PDF.
* On Google Chrome:
  * Set **Margin** to **None**.
  * Print **Background Graphics**.
  * Don't print headers and footers.
  * Save as PDF.
