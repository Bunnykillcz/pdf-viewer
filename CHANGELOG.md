## 2.2.0

  - fix issue #8 : On IE11, the document isn't centered into the page
  - improves performance : redraws the page only when it's necessary

## 2.1.1

  - fix issue #7 : Page Number is resetting to 1 when loading a document
  - use importPath to load the pdf worker script `pdf.worker.min.js`

## 2.1.0

 - update to PDFjs 2.0.426
 - adds events :
   - pdf-viewer-outrange: when trying to display a page that doesn't exist
   - pdf-viewer-render: when the page has been rendered
 - fix : this._PDF.getPage is not a function

## 2.0.1

 - add a property to declare the PDFJS worker script
 - update doc 

## 2.0.0

 - update to polymer 2.x

## 1.0.1

 - fix #1 : Drag'n drop to move pdf in the viewer not working in es5 version
 - README : adds a note about document loading

## 1.0.0

public release
