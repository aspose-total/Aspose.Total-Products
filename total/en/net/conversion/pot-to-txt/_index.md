---
title: Convert POT to TXT via C# .NET 
url_ignore: /net/conversion/pot-to-txt/ 
description: Convert PowerPoint pot documents to Word txt files with C#. Convert multiple files within ASP.NET or other .NET applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert POT to TXT using C#" h2="Build Microsoft PowerPoint POT Presentation to Word TXT document conversion apps on .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docsLink="https://docs.aspose.com/total/net" installationsDocsLink="https://docs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert POT to TXT Using C#" %}}

 In order to automate the process for any PowerPoint pot presentation to Word txt files batch conversion , we’ll use [Aspose.Slides for .NET](https://products.aspose.com/slides/net) and [Aspose.Words for .NET](https://products.aspose.com/words/net) APIs. The former is a PowerPoint presentation manipulation API that lets you create or modify Microsoft PowerPoint slides. Whereas, the latter is a word processing API for processing or manipulating Microsoft Word documents. Both APIs are part of [Aspose.Total for .NET](https://products.aspose.com/total/net) package. You can directly [download](https://downloads.aspose.com/) from Nuget or may use the following commands from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs
PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert POT to TXT via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total makes it easy for the developers to load & convert POT files to TXT in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Add reference of Aspose.Slides for .NET and Aspose.Words for .NET
1. Load PowerPoint POT presentation using [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
1. Save the document into [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Object
1. Create [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) and intialize it with MemoryStream Object
1. Save the document using [Aspose.Words.Document.Save("output.txt", SaveFormat.Txt)](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites. 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Slides for .NET and Aspose.Words for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This code sample shows how to convert a POT to TXT using C#" offSpacer="" %}}

```cs// Load the Microsoft PowerPoint POT file
Aspose.Slides.Presentation pot = new Aspose.Slides.Presentation("source.pot");

var stream = new MemoryStream();

pot.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var txt = new Aspose.Words.Document(stream);
      
// Save the Word TXT document
txt.Save("output.txt", Aspose.Words.SaveFormat.Txt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert POT to TXT" sectionDescription="Check our live demos for [POT to TXT conversion](https://products.aspose.app/slides/conversion/) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POT file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant TXT file." >}}

    {{% blocks/products/pf/agp/content h2="About Aspose.Total" %}}

Aspose.Total for .NET is complete package of document Manipulation APIs. APIs are easily integratable within any .NET based application to manipulate Microsoft Word, Excel, PowerPoint, Outlook, PDF, Images, Barcodes and more than 100 other formats. Programmers can easily use these to create, modify, render, print and convert between most popular file formats within any .NET, C#, ASP.NET and VB.NET applications without the need of any other software.



    {{% /blocks/products/pf/agp/content %}}

    

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert POT into many other file formats including few listed below." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-doc" name="POT To DOC" description="Microsoft Word Binary Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-docx" name="POT To DOCX" description="Office 2007+ Words Document" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-rtf" name="POT To RTF" description="Rich Text Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-dot" name="POT To DOT" description="Microsoft Word Template Files" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-dotx" name="POT To DOTX" description="Microsoft Word Template File " >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-dotm" name="POT To DOTM" description="Microsoft Word 2007+ Template File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-docm" name="POT To DOCM" description="Microsoft Word 2007 Marco File" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-flatopc" name="POT To FLATOPC" description="Microsoft Word 2003 WordprocessingML format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-odt" name="POT To ODT" description="OpenDocument Text File Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-ott" name="POT To OTT" description="OpenDocument Standard Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-wordml" name="POT To WORDML" description="Microsoft Word 2003 WordprocessingML format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/net/conversion/pot-to-txt" name="POT To TXT" description="Text Document" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}