---
title: Convert TXT to PPSM via C# .NET 
url_ignore: /net/conversion/txt-to-ppsm/ 
description: Convert Word txt documents to PowerPoint ppsm files with C#. Convert multiple files within ASP.NET or other .NET applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert TXT to PPSM using C#" h2="Build Microsoft Word TXT to PowerPoint PPSM conversion apps on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docsLink="https://docs.aspose.com/total/net" installationsDocsLink="https://docs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert TXT to PPSM Using C#" %}}

 In order to automate the process for any Word txt files to PowerPoint ppsm presentation batch conversion , we’ll use [Aspose.Words for .NET](https://products.aspose.com/words/net) and [Aspose.Slides for .NET](https://products.aspose.com/slides/net) APIs. The former is a word processing API for processing or manipulating Microsoft Word documents. Whereas, the latter is a presentation manipulation API that lets you create or modify Microsoft PowerPoint slides. Both APIs are part of [Aspose.Total for .NET](https://products.aspose.com/total/net) package. You can directly [download](https://downloads.aspose.com/) from Nuget or may use the following commands from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs
PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert TXT to PPSM via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total makes it easy for the developers to load & convert TXT files to PPSM in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Add reference of Aspose.Total for .NET
1. Load TXT file using [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) class
1. Save the TXT document into HTML
1. Create [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) Object
1. Import HTML content in text frame of any slide shape inside presentation
1. Save the document using [Aspose.Slides.Presentation.Save("output.ppsm", SaveFormat.Ppsm)](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites. 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Words for .NET &amp; Aspose.Slides for .NET DLLs or Aspose.Total for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This code sample shows how to convert a TXT to PPSM using C#" offSpacer="" %}}

```cs// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPSM.

using (Presentation ppsm = new Presentation()){

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

	// Save the PPSM Presentation
	ppsm.Save("filepath\\pres.ppsm", Aspose.Slides.Export.SaveFormat.Ppsm);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert TXT to PPSM" sectionDescription="Check our live demos for [TXT to PPSM conversion](https://products.aspose.app/words/conversion/word-to-ppsm) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your TXT file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSM file." >}}

    {{% blocks/products/pf/agp/content h2="About Aspose.Total" %}}

Aspose.Total for .NET is complete package of document Manipulation APIs. APIs are easily integratable within any .NET based application to manipulate Microsoft Word, Excel, PowerPoint, Outlook, PDF, Images, Barcodes and more than 100 other formats. Programmers can easily use these to create, modify, render, print and convert between most popular file formats within any .NET, C#, ASP.NET and VB.NET applications without the need of any other software.



    {{% /blocks/products/pf/agp/content %}}

    

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert TXT into many other file formats including few listed below." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-ppt/" name="TXT To PPT" description="Microsoft PowerPoint 97-2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-pptx/" name="TXT To PPTX" description="Open XML presentation Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-pps/" name="TXT To PPS" description="PowerPoint Slide Show" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-pot/" name="TXT To POT" description="Microsoft PowerPoint Template Files" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-ppsx/" name="TXT To PPSX" description="PowerPoint Slide Show" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-pptm/" name="TXT To PPTM" description="Macro-enabled Presentation File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-ppsm/" name="TXT To PPSM" description="Macro-enabled Slide Show" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-potx/" name="TXT To POTX" description="Microsoft PowerPoint Template Presentation" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-potm/" name="TXT To POTM" description="Microsoft PowerPoint Template File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/txt-to-odp/" name="TXT To ODP" description="OpenDocument Presentation Format" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}