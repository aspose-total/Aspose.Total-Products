---
title: Convierta DOTM a PPS a través de C++
description: Exporte DOTM a PPS en sus aplicaciones C++ sin usar Microsoft Word o PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: PPS
otherformats: ODP POTM PPTX POTX PPTM PPT POWERPOINT PPSX POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir DOTM a PPS" h2="Exporte DOTM a PPS dentro de sus aplicaciones C++ sin usar Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consta de potentes API de automatización de archivos que permiten automatizar la conversión de DOTM a PPS al usar dos de sus API. Cargue su DOTM usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) y conviértalo a HTML, luego cargue el HTML mediante la manipulación de PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para crear una nueva presentación y guardarla como PPS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de DOTM a PPS en C++" %}}
1. Abra el archivo DOTM usando la referencia de clase [Dotmumento](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
2. Convierta DOTM a HTML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_stdbasicostream_saveoptions)
3. Inicialice un nuevo objeto [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Agregue una autoforma en su diapositiva y agregue AddTextFrame en ella
5. Cargue el contenido HTML y escríbalo en su archivo de presentación
6. Guarde el dotmumento en formato PPS usando el método [Guardar](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Pps como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTM file with an instance of Dotmument
Dotmument dotmument = new Dotmument("template.dotm");
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"sourceFile.dotm");
// save the dotmument in HTML file format
dotm->Save(u"HtmlOutput.HTML");
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cargar dotmumento DOTM protegido por contraseña a través de C++" %}}
Además de la conversión de dotmumentos, la API de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite toneladas de funciones de manipulación de dotmumentos para los desarrolladores de C++. En caso de que su formato de archivo DOTM de Microsoft Word esté protegido con contraseña, aún puede abrirlo usando la API. Para cargar el dotmumento cifrado, puede utilizar una sobrecarga de constructor especial, que acepta un objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotmument, the password is passed to the dotmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotmPassword");
// load the dotmument from the local file system by filename:
SharedPtr<Dotmument> dotm = MakeObject<Dotmument>(u"Encrypted.dotm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregar comentarios en el dotmumento PPS a través de C++" %}}
Mientras guarda DOTM como PPS, también puede usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para agregar más funciones en su dotmumento PPS. Por ejemplo, puede agregar comentarios en su presentación. El comentario de la diapositiva de la presentación está asociado con un autor en particular. La clase Presentation contiene la colección de autores en ICommentAuthorCollection que son responsables de agregar comentarios de diapositivas. Para cada autor, hay una colección de comentarios en ICommentCollection.
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-pps/" name="DOTM A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-potm/" name="DOTM A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-pptx/" name="DOTM A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-potx/" name="DOTM A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-pptm/" name="DOTM A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-ppt/" name="DOTM A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-powerpoint/" name="DOTM A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-ppsx/" name="DOTM A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-pot/" name="DOTM A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/dotm-to-ppsm/" name="DOTM A PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}