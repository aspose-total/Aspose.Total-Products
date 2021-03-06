---
title: Convierta FLATOPC a POT a través de C# .NET 
url: /es/net/conversion/flatopc-to-pot/ 
description: Convierta documentos de Word flatopc en archivos pot de PowerPoint con C#. Convierta múltiples archivos dentro de ASP.NET u otras aplicaciones .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convierta FLATOPC a POT usando C#" h2="Cree aplicaciones de conversión de Microsoft Word FLATOPC a PowerPoint POT en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" flatopcsLink="https://flatopcs.aspose.com/total/net" installationsFlatopcsLink="https://flatopcs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://flatopcs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir FLATOPC a POT usando C#" %}}

Para automatizar el proceso de cualquier archivo de documento de Word a la conversión por lotes de presentación de PowerPoint pot, usaremos [Aspose.Words for .NET](https://products.aspose.com/words/net) y [Aspose.Slides para .NET](https://products.aspose.com/slides/net) API. La primera es una API de procesamiento de textos para procesar o manipular documentos de Microsoft Word. Mientras que esta última es una API de manipulación de presentaciones que le permite crear o modificar diapositivas de Microsoft PowerPoint. Ambas API forman parte del paquete [Aspose.Total for .NET](https://products.aspose.com/total/net). Puede [descargar] directamente (https://downloads.aspose.com/) desde Nuget o puede usar los siguientes comandos desde la consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir FLATOPC a POT a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Agregar referencia de Aspose.Total para .NET
1. Cargue el archivo FLATOPC usando la clase [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Guarde el documento FLATOPC en HTML
1. Cree el objeto [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importe contenido HTML en el marco de texto de cualquier forma de diapositiva dentro de la presentación
1. Guarde el documento usando [Aspose.Slides.Presentation.Save("output.pot", SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.Words para .NET &amp; Aspose.Slides para .NET DLL o Aspose.Total para .NET DLL a las que se hace referencia en su proyecto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este ejemplo de código muestra cómo convertir un FLATOPC a POT usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word FLATOPC file
Aspose.Words.Document flatopc = new Aspose.Words.Document("sourceWordFile.flatopc");

// Save FLATOPC file to HTML 
flatopc.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages FLATOPC documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

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

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir FLATOPC a POT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-ppt/" name="FLATOPC A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-pptx/" name="FLATOPC A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-pps/" name="FLATOPC A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-pot/" name="FLATOPC A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-ppsx/" name="FLATOPC A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-pptm/" name="FLATOPC A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-ppsm/" name="FLATOPC A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-potx/" name="FLATOPC A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-potm/" name="FLATOPC A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/flatopc-to-pot/" name="FLATOPC A POT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}