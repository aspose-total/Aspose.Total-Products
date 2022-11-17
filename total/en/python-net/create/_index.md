---
title: Create File using Python 

description: Create text and Microsoft Word documents with out installing Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Create Documents using Python" h2="Create Text and Microsoft Word DOCX, DOC files within Python Applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Storing data is the basic of any software application depending on the application nature. Storing location may be the database, XML, JSON, text files, Excel reports or Microsoft Word documents. File I/O is the part of any language and mostly languages including Python supports writing data to text files. Let's consider the Python language. Writing existing text files using Python, It provides open, write and close method for this tasks. Firstly open the file with relevant file path and append or write feature as arguments. Then write the required text into file and lastly close the file using close() method. 

For creating Microsoft Word documents using Python, We use Aspose.Total for Python via .NET APIs package that has Aspose.Words for Python via .NET API as part of its package. This API provides full document automation solution for invoices, reports and technical articles. Procedure of word document creation listed below.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="How to Create Text File using Python" %}}

Creating and writing to text files is simple. Python provides open() method with three parameters and have to use one of the parameter along with the file path. Three parameters are "x", "a" and "w". By providing "x", new file will be created but throws error in case the file already exists. By providing "a", new text file will be created if does not exists and in case it exists, content will be appended at the end. And lastly providing "w", new text document will be created and overwrited with the new content in case the it exists already.

{{% blocks/products/pf/feature-page-code h3="Python - Create Text File" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Microsoft Word Documents" %}}

Total Python Word API has multiple features including creation of Microsoft Word files, inserting images and text within documents, add tables and lists witin the files as well as modifying existing documents with ease. To create Microsoft Word document process, create the object of Document and DocumentBuilder classes. Add the required text, paragraph, lists and tables within the document and finally save it.

{{% blocks/products/pf/feature-page-code h3="Python - Create Microsoft Word Documents" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}