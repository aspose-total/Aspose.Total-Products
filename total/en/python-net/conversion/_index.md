---
title: Document Conversion via Python 

description: Convert Microsoft Word Formats DOC, DOCX to PDF, Images and more as well as Presentation Slides, Email Messages and 3D Images just few lines of Python code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Document Conversion using Python APIs" h2="Convert Microsoft<sup>&reg;</sup> Office Word, PDF, Images and various other formats using Aspose.Words for Python via .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python APIs](https://products.aspose.com/total/python-net/) speeds up developing document automation solutions from scratch or enhancing existing applications to create, edit or convert documents, presentations, emails and 3D files. Python API not only handles Microsoft Office Word and Presentation slides but also handles PDF, HTML, Images and Email files and a lot more. API does not depend on any software and is a full set of document management and manipulation solution.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Word to PDF" %}}
Total Python API supports multiple conversion of formats such as Microsoft Word to PDF, Images, Markdown and HTML. API makes the process of converting Word document to PDF simple with the quality output as close to the document as of DOC, DOCX file. Process is load the DOC or DOCX file into [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) object and just call the [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) method with target PDF format along with its directory path. It's so simple. In case there is need to specify PDF standards like PDF 1.7 or 1.5, API provides [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) enumeration, for setting [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python - Word to PDF Conversion" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-images pdf-to-mhtml" >}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word to Images Conversion" %}}
Word to Images Conversion is anthor feature of Python API. Besides just conversion, one can easily set various save options such as brightness, contrast,  horizontal and vertical resolution etc. Process is, load the document via Document object and then call the save method with the desired image file extion having specified path. To specify various save options, API provides  [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) or [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) classes can be used as of the required scenario. Below code sample demonstrates creating a preview of the first document page with applying some additional settings.

{{% blocks/products/pf/feature-page-code h3="Python - Word to Image Conversion" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="docx-to-images rtf-to-images mhtml-to-images mhtml-to-rtf mhtml-to-doc" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft PowerPoint to Word" %}}
Python API supports converting Microsoft PowerPoint PPT / PPTX to Word DOC / DOCX files. Two APIs [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) and [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) used to perform this conversion. Load the PPT / PPTX file using [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Get the Words Document class object. Iterate through each slide, generates and inserts slide image and then insert the slide text by iterating through slides shapes.

{{% blocks/products/pf/feature-page-code h3="Python - PowerPoint Slides to Word Conversion" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}