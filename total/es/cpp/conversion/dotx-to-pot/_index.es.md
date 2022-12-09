---
title: Convierta DOTX a POT a través de C++
description: Exporte DOTX a POT en sus aplicaciones C++ sin usar Microsoft Word o PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: POT
otherformats: PPT POTX PPSX PPTM ODP POTM PPS POWERPOINT PPSM PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir DOTX a POT" h2="Exporte DOTX a POT dentro de sus aplicaciones C++ sin usar Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consta de potentes API de automatización de archivos que permiten automatizar la conversión de DOTX a POT al usar dos de sus API. Cargue su DOTX usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) y conviértalo a HTML, luego cargue el HTML mediante la manipulación de PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para crear una nueva presentación y guardarla como POT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de DOTX a POT en C++" %}}
1. Abra el archivo DOTX usando la referencia de clase [Dotxumento](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Convierta DOTX a HTML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. Inicialice un nuevo objeto [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Agregue una autoforma en su diapositiva y agregue AddTextFrame en ella
5. Cargue el contenido HTML y escríbalo en su archivo de presentación
6. Guarde el dotxumento en formato POT usando el método [Guardar](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Pot como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cargar dotxumento DOTX protegido por contraseña a través de C++" %}}
Además de la conversión de dotxumentos, la API de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite toneladas de funciones de manipulación de dotxumentos para los desarrolladores de C++. En caso de que su formato de archivo DOTX de Microsoft Word esté protegido con contraseña, aún puede abrirlo usando la API. Para cargar el dotxumento cifrado, puede utilizar una sobrecarga de constructor especial, que acepta un objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregar comentarios en el dotxumento POT a través de C++" %}}
Mientras guarda DOTX como POT, también puede usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para agregar más funciones en su dotxumento POT. Por ejemplo, puede agregar comentarios en su presentación. El comentario de la diapositiva de la presentación está asociado con un autor en particular. La clase Presentation contiene la colección de autores en ICommentAuthorCollection que son responsables de agregar comentarios de diapositivas. Para cada autor, hay una colección de comentarios en ICommentCollection.
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-ppt/" name="DOTX A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-potx/" name="DOTX A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-ppsx/" name="DOTX A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-pptm/" name="DOTX A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-pot/" name="DOTX A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-potm/" name="DOTX A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-pps/" name="DOTX A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-powerpoint/" name="DOTX A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-ppsm/" name="DOTX A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotx-to-pptx/" name="DOTX A PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}