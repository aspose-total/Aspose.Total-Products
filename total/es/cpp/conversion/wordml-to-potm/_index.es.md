---
title: Convierta WORDML a POTM a través de C++
description: Exporte WORDML a POTM en sus aplicaciones C++ sin usar Microsoft Word o PowerPoint
url: /es/cpp/conversion/wordml-to-potm/
family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: POTM
otherformats: PPSX POT PPTM POWERPOINT PPT ODP PPS POTX PPTX PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir WORDML a POTM" h2="Exporte WORDML a POTM dentro de sus aplicaciones C++ sin usar Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para C++](https://products.aspose.com/total/cpp/) consta de potentes API de automatización de archivos que permiten automatizar la conversión de WORDML a POTM al usar dos de sus API. Cargue su WORDML usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) y conviértalo a HTML, luego cargue el HTML mediante la manipulación de PowerPoint C++ API [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) para crear una nueva presentación y guardarla como POTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de WORDML a POTM en C++" %}}
1. Abra el archivo WORDML usando la referencia de clase [Wordmlumento](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
2. Convierta WORDML a HTML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions)
3. Inicialice un nuevo objeto [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Agregue una autoforma en su diapositiva y agregue AddTextFrame en ella
5. Cargue el contenido HTML y escríbalo en su archivo de presentación
6. Guarde el wordmlumento en formato POTM usando el método [Guardar](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Potm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cargar wordmlumento WORDML protegido por contraseña a través de C++" %}}
Además de la conversión de wordmlumentos, la API de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite toneladas de funciones de manipulación de wordmlumentos para los desarrolladores de C++. En caso de que su formato de archivo WORDML de Microsoft Word esté protegido con contraseña, aún puede abrirlo usando la API. Para cargar el wordmlumento cifrado, puede utilizar una sobrecarga de constructor especial, que acepta un objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregar comentarios en el wordmlumento POTM a través de C++" %}}
Mientras guarda WORDML como POTM, también puede usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para agregar más funciones en su wordmlumento POTM. Por ejemplo, puede agregar comentarios en su presentación. El comentario de la diapositiva de la presentación está asociado con un autor en particular. La clase Presentation contiene la colección de autores en ICommentAuthorCollection que son responsables de agregar comentarios de diapositivas. Para cada autor, hay una colección de comentarios en ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-ppsx/" name="WORDML A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-pot/" name="WORDML A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-pptm/" name="WORDML A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-powerpoint/" name="WORDML A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-ppt/" name="WORDML A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-potm/" name="WORDML A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-pps/" name="WORDML A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-potx/" name="WORDML A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-pptx/" name="WORDML A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/wordml-to-ppsm/" name="WORDML A PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}