---
title: Convierta DOC a PPTM a través de C++ o con el convertidor en línea gratuito
description: Exporte DOC a PPTM en sus aplicaciones C++ sin usar Microsoft Word o PowerPoint o en línea. Pruebe el convertidor en línea gratuito de DOC a PPTM rápidamente antes de integrar el código.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPTM
otherformats: POT PPSX PPT POTX ODP POTM PPS PPSM POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir DOC a PPTM o aplicación en línea" h2="Exporte DOC a PPTM dentro de sus aplicaciones C++ sin usar Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consta de potentes API de automatización de archivos que permiten automatizar la conversión de DOC a PPTM al usar dos de sus API. Cargue su DOC usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) y conviértalo a HTML, luego cargue el HTML mediante la manipulación de PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para crear una nueva presentación y guardarla como PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de DOC a PPTM en C++" %}}
1. Abra el archivo DOC usando la referencia de clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Convierta DOC a HTML usando la función miembro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Inicialice un nuevo objeto [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Agregue una autoforma en su diapositiva y agregue AddTextFrame en ella
5. Cargue el contenido HTML y escríbalo en su archivo de presentación
6. Guarde el documento en formato PPTM usando el método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Pptm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertidor en línea gratuito para DOC a PPTM</h3>

<iframe title="Herramienta de conversión de pptm a doc" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptm&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Cargar documento DOC protegido por contraseña a través de C++" %}}
Además de la conversión de documentos, la API de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite toneladas de funciones de manipulación de documentos para los desarrolladores de C++. En caso de que su formato de archivo DOC de Microsoft Word esté protegido con contraseña, aún puede abrirlo usando la API. Para cargar el documento cifrado, puede utilizar una sobrecarga de constructor especial, que acepta un objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregar comentarios en el documento PPTM a través de C++" %}}
Mientras guarda DOC como PPTM, también puede usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para agregar más funciones en su documento PPTM. Por ejemplo, puede agregar comentarios en su presentación. El comentario de la diapositiva de la presentación está asociado con un autor en particular. La clase Presentation contiene la colección de autores en ICommentAuthorCollection que son responsables de agregar comentarios de diapositivas. Para cada autor, hay una colección de comentarios en ICommentCollection.
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
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
                          <span itemprop="name"><b>¿Cómo puedo convertir DOC a PPTM en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede encontrar la aplicación en línea para la conversión de DOC arriba. Para iniciar el proceso de conversión, puede agregar el archivo DOC arrastrándolo y soltándolo o haciendo clic dentro del área blanca para importar el documento. Una vez que haya agregado el archivo, puede simplemente hacer clic en el botón "Convertir". Una vez que se completa la conversión de DOC a PPTM, puede descargar su archivo convertido con solo un clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir DOC?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La velocidad de este convertidor en línea depende en gran medida del tamaño del archivo DOC que se convierte. Los archivos DOC pequeños se pueden convertir a PPTM en solo unos segundos. Si está utilizando el código de conversión dentro de una aplicación C++, la velocidad de conversión dependerá de qué tan bien haya optimizado su aplicación.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir DOC a PPTM usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Después de que su archivo DOC se convierta a PPTM utilizando nuestro convertidor en línea, el enlace de descarga para el archivo PPTM estará disponible de inmediato. Nos tomamos muy en serio la seguridad y la privacidad de sus archivos cargados y los eliminamos 24 horas después de que se completa el proceso de conversión. Tenga la seguridad de que nadie tendrá acceso a sus archivos. Nuestro proceso de conversión, incluida la conversión de DOC, es completamente seguro. Proporcionamos una aplicación gratuita con fines de prueba para que pueda verificar los resultados antes de integrar el código.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir DOC?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Para la conversión de DOC en línea, puede usar cualquier navegador moderno, como Google Chrome, Firefox, Opera o Safari. Sin embargo, si está desarrollando una aplicación de escritorio, se recomienda Aspose.Total DOC Conversion API para un rendimiento sin problemas.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}