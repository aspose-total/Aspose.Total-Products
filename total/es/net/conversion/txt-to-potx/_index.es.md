---
title: Convierta TXT a POTX a través de C# .NET o con el convertidor en línea gratuito
description: Convierta documentos de Word txt en archivos potx de PowerPoint con C#. Convierta múltiples archivos dentro de ASP.NET u otras aplicaciones .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta TXT a POTX usando C# o en línea" h2="Cree aplicaciones de conversión de Microsoft Word TXT a PowerPoint POTX en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Cómo convertir TXT a POTX usando C#" %}}

Para automatizar el proceso de cualquier archivo de documento de Word a la conversión por lotes de presentación de PowerPoint potx, usaremos [Aspose.Words for .NET](https://products.aspose.com/words/net) y [Aspose.Slides para .NET](https://products.aspose.com/slides/net) API. La primera es una API de procesamiento de textos para procesar o manipular documentos de Microsoft Word. Mientras que esta última es una API de manipulación de presentaciones que le permite crear o modificar diapositivas de Microsoft PowerPoint. Ambas API forman parte del paquete [Aspose.Total for .NET](https://products.aspose.com/total/net). Puede [descargar] directamente (https://releases.aspose.com/) desde Nuget o puede usar los siguientes comandos desde la consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir TXT a POTX a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Agregar referencia de Aspose.Total para .NET
1. Cargue el archivo TXT usando la clase [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Guarde el documento TXT en HTML
1. Cree el objeto [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importe contenido HTML en el marco de texto de cualquier forma de diapositiva dentro de la presentación
1. Guarde el documento usando [Aspose.Slides.Presentation.Save("output.potx", SaveFormat.Potx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.Words para .NET &amp; Aspose.Slides para .NET DLL o Aspose.Total para .NET DLL a las que se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este ejemplo de código muestra cómo convertir un TXT a POTX usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POTX.

using (Presentation potx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the POTX Presentation
	potx.Save("filepath\\pres.potx", Aspose.Slides.Export.SaveFormat.Potx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertidor en línea de TXT a POTX</h3>

<iframe title="Herramienta de conversión de potx a txt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=potx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir TXT a POTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos TXT a POTX mediante programación: casos de uso" %}}
Convertir archivos de texto a potx: desbloquear la potencia completa de tus documentos

Los archivos de texto se han convertido en una parte esencial de la comunicación digital, ofreciendo un formato de texto plano que se puede compartir fácilmente y acceder. Sin embargo, cuando se trata de crear presentaciones visuales atractivas, los archivos potx toman el centro del escenario. La conversión de archivos de texto a formatos potx es necesaria para desbloquear las capacidades de presentación completas de tus documentos.

Esta conversión te permite:

**Uso de casos:**

*   **Presentaciones comerciales**: Convierte archivos de texto para crear presentaciones empresariales atractivas, con slides, imágenes y contenido multimedia.
*   **Investigación académica**: Usa potx para crear papeles de investigación profesionales, tesis y tesis, con tablas, figuras y gráficos.
*   **Materiales de marketing**: Convierte archivos de texto para crear materiales de marketing efectivos, como scripts comerciales, descripciones de productos y copias publicitarias.
*   **Contenido educativo**: Crea contenido educativo interactivo, como planes de lección, pruebas y evaluaciones, utilizando el formato potx.
*   **Documentación técnica**: Usa potx para crear documentación técnica completa, incluyendo guías de usuario, instrucciones y documentación de sistema.

Al convertir tus archivos de texto a potx, puedes elevar la apariencia visual de tus documentos, haciéndolos más atractivos e efectivos para diferentes propósitos.
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
                          <span itemprop="name"><b>¿Cómo puedo convertir TXT a POTX en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La aplicación en línea para la conversión de TXT está integrada arriba. Para usar esta aplicación, puede agregar su archivo TXT arrastrándolo y soltándolo en el área blanca designada o haciendo clic dentro del área para importar el documento. A continuación, presione el botón Convertir para iniciar el proceso de conversión. Una vez que se completa la conversión de TXT a POTX, puede descargar su archivo recién convertido con solo un clic, y estará disponible para usted en forma de archivo POTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Este convertidor en línea funciona rápidamente, pero depende principalmente del tamaño del archivo TXT que se está convirtiendo. Para archivos TXT pequeños, la conversión a POTX se puede completar en cuestión de segundos. Sin embargo, si ha integrado el código de conversión dentro de una aplicación .NET, la velocidad de conversión dependerá de qué tan bien se haya optimizado su aplicación para el proceso de conversión.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir TXT a POTX usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Una vez que se completa la conversión de TXT a POTX, el enlace de descarga para el archivo POTX recién convertido estará disponible al instante. También garantiza la seguridad del proceso de conversión, ya que todos los archivos cargados, incluidos los archivos TXT, son completamente seguros y se eliminarán del sistema después de 24 horas. Además, los enlaces de descarga dejarán de funcionar después de este período, lo que garantiza la privacidad y protección de sus archivos. La aplicación integrada es de uso gratuito y está diseñada con fines de prueba para que los usuarios puedan evaluar los resultados antes de integrar el código en sus proyectos.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede usar cualquier navegador web moderno, como Google Chrome, Firefox, Opera o Safari, para la conversión en línea de TXT a POTX. Sin embargo, si está desarrollando una aplicación de escritorio, se recomienda la API de conversión TXT de Aspose.Total para un procesamiento fluido y eficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}