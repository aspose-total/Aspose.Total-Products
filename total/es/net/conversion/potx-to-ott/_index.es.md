---
title: Convierta POTX a OTT a través de C# .NET o con el convertidor en línea gratuito
description: Convierta documentos potx de PowerPoint en archivos ott de Word con C#. Convierta múltiples archivos dentro de ASP.NET u otras aplicaciones .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta POTX a OTT usando C# o en línea" h2="Cree aplicaciones de conversión de presentaciones de Microsoft PowerPoint POTX a documentos OTT de Word en las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Cómo convertir POTX a OTT usando C#" %}}

Para automatizar el proceso de conversión por lotes de cualquier presentación POTX de PowerPoint a archivos de documentos de Word, usaremos [Aspose.Slides for .NET](https://products.aspose.com/slides/net) y [Aspose.Words para .NET](https://products.aspose.com/words/net) API. La primera es una API de manipulación de presentaciones de PowerPoint que le permite crear o modificar diapositivas de Microsoft PowerPoint. Mientras que este último es una API de procesamiento de textos para procesar o manipular documentos de Microsoft Word. Ambas API forman parte del paquete [Aspose.Total for .NET](https://products.aspose.com/total/net). Puede [descargar] directamente (https://releases.aspose.com/) desde Nuget o puede usar los siguientes comandos desde la consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir POTX a OTT a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Agregar referencia de Aspose.Slides para .NET y Aspose.Words para .NET
1. Cargue la presentación de PowerPoint POTX usando la clase [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Guarde el documento en [MemoryStream](https://otts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Objeto
1. Cree [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) e inicialícelo con MemoryStream Object
1. Guarde el documento usando [Aspose.Words.Document.Save("output.ott", SaveFormat.Ott)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.Slides para .NET y Aspose.Words para .NET DLL a las que se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este ejemplo de código muestra cómo convertir un POTX a OTT usando C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTX file
Aspose.Slides.Presentation potx = new Aspose.Slides.Presentation("source.potx");

var stream = new MemoryStream();

potx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var ott = new Aspose.Words.Document(stream);
      
// Save the Word OTT document
ott.Save("output.ott", Aspose.Words.SaveFormat.Ott);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertidor en línea de POTX a OTT</h3>

<iframe title="Herramienta de conversión de ott a potx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ott&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir POTX a OTT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
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
                          <span itemprop="name"><b>¿Cómo puedo convertir POTX a OTT en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La aplicación en línea para la conversión de POTX está integrada arriba. Para usar la aplicación, puede agregar su archivo POTX arrastrándolo y soltándolo en el área designada o haciendo clic dentro del área para importar el archivo. Una vez agregado el archivo, haga clic en el botón Convertir para iniciar el proceso de conversión. Una vez completada la conversión de POTX a OTT, puede descargar su archivo recién convertido con solo un clic y estará disponible en formato OTT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">este convertidor en línea es rápido, pero la velocidad de la conversión de POTX a OTT depende principalmente del tamaño del archivo POTX que se convierte. Los archivos POTX más pequeños se pueden convertir en formato OTT en cuestión de segundos. Además, si ha integrado el código de conversión de POTX a OTT dentro de una aplicación .NET, la velocidad de conversión dependerá de qué tan bien haya optimizado su aplicación para el proceso de conversión.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir POTX a OTT usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Una vez que se complete el proceso de conversión de POTX a OTT, el enlace de descarga para el archivo OTT convertido estará disponible al instante. Todos los archivos cargados, incluidos los archivos POTX, se eliminan del sistema después de 24 horas y los enlaces de descarga dejan de funcionar después de este período de tiempo. El convertidor en línea garantiza la seguridad y privacidad de sus archivos, y la aplicación integrada está disponible sin costo para realizar pruebas. Esto permite a los usuarios comprobar el resultado antes de integrar el código en sus proyectos.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede utilizar cualquier navegador web contemporáneo como Google Chrome, Firefox, Opera o Safari para convertir archivos POTX a OTT en línea. Sin embargo, si está creando una aplicación de escritorio, se recomienda la API de conversión POTX de Aspose.Total para un proceso de conversión fluido y fluido.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}