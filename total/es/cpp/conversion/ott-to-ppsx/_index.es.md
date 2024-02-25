---
title: Convierta OTT a PPSX a través de C++ o con el convertidor en línea gratuito
description: Exporte OTT a PPSX en sus aplicaciones C++ sin usar Microsoft Word o PowerPoint o en línea. Pruebe el convertidor en línea gratuito de OTT a PPSX rápidamente antes de integrar el código.

family: total
platformtag: cpp
feature: conversion
informat: OTT
outformat: PPSX
otherformats: POTM ODP PPTX PPTM PPSM POTX PPT POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir OTT a PPSX o aplicación en línea" h2="Exporte OTT a PPSX dentro de sus aplicaciones C++ sin usar Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consta de potentes API de automatización de archivos que permiten automatizar la conversión de OTT a PPSX al usar dos de sus API. Cargue su OTT usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) y conviértalo a HTML, luego cargue el HTML mediante la manipulación de PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para crear una nueva presentación y guardarla como PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de OTT a PPSX en C++" %}}
1. Abra el archivo OTT usando la referencia de clase [Ottumento](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
2. Convierta OTT a HTML usando la función miembro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_stdbasicostream_saveoptions)
3. Inicialice un nuevo objeto [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Agregue una autoforma en su diapositiva y agregue AddTextFrame en ella
5. Cargue el contenido HTML y escríbalo en su archivo de presentación
6. Guarde el ottumento en formato PPSX usando el método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Ppsx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load OTT file with an instance of Ottument
Ottument ottument = new Ottument("template.ott");
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"sourceFile.ott");
// save the ottument in HTML file format
ott->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertidor en línea gratuito para OTT a PPSX</h3>

<iframe title="Herramienta de conversión de ppsx a ott" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsx&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Cargar ottumento OTT protegido por contraseña a través de C++" %}}
Además de la conversión de ottumentos, la API de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite toneladas de funciones de manipulación de ottumentos para los desarrolladores de C++. En caso de que su formato de archivo OTT de Microsoft Word esté protegido con contraseña, aún puede abrirlo usando la API. Para cargar el ottumento cifrado, puede utilizar una sobrecarga de constructor especial, que acepta un objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected ottument, the password is passed to the ottument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"ottPassword");
// load the ottument from the local file system by filename:
SharedPtr<Ottument> ott = MakeObject<Ottument>(u"Encrypted.ott", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregar comentarios en el ottumento PPSX a través de C++" %}}
Mientras guarda OTT como PPSX, también puede usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para agregar más funciones en su ottumento PPSX. Por ejemplo, puede agregar comentarios en su presentación. El comentario de la diapositiva de la presentación está asociado con un autor en particular. La clase Presentation contiene la colección de autores en ICommentAuthorCollection que son responsables de agregar comentarios de diapositivas. Para cada autor, hay una colección de comentarios en ICommentCollection.
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Preguntas frecuentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cómo puedo convertir OTT a PPSX en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede encontrar la aplicación en línea para la conversión de OTT arriba. Para iniciar el proceso de conversión, puede agregar el archivo OTT arrastrándolo y soltándolo o haciendo clic dentro del área blanca para importar el documento. Una vez que haya agregado el archivo, puede simplemente hacer clic en el botón "Convertir". Una vez que se completa la conversión de OTT a PPSX, puede descargar su archivo convertido con solo un clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La velocidad de este convertidor en línea depende en gran medida del tamaño del archivo OTT que se convierte. Los archivos OTT pequeños se pueden convertir a PPSX en solo unos segundos. Si está utilizando el código de conversión dentro de una aplicación C++, la velocidad de conversión dependerá de qué tan bien haya optimizado su aplicación.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir OTT a PPSX usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Después de que su archivo OTT se convierta a PPSX utilizando nuestro convertidor en línea, el enlace de descarga para el archivo PPSX estará disponible de inmediato. Nos tomamos muy en serio la seguridad y la privacidad de sus archivos cargados y los eliminamos 24 horas después de que se completa el proceso de conversión. Tenga la seguridad de que nadie tendrá acceso a sus archivos. Nuestro proceso de conversión, incluida la conversión de OTT, es completamente seguro. Proporcionamos una aplicación gratuita con fines de prueba para que pueda verificar los resultados antes de integrar el código.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Para la conversión de OTT en línea, puede usar cualquier navegador moderno, como Google Chrome, Firefox, Opera o Safari. Sin embargo, si está desarrollando una aplicación de escritorio, se recomienda Aspose.Total OTT Conversion API para un rendimiento sin problemas.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}