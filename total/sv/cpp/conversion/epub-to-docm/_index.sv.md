---
title: C++ API för att exportera EPUB till DOCM
description: Konvertera EPUB till DOCM inom C++-applikationer.
url: /sv/cpp/conversion/epub-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: DOCM
otherformats: ODT PCL MHTML XAMLFLOW DOTX MARKDOWN WORDML OTT DOT FLATOPC DOTM PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera EPUB till DOCM" h2="Återge EPUB till DOCM inom C++-applikationer utan att kräva någon tredjepartsapplikation" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) filformatsautomatiseringsbibliotek tillåter C++-utvecklare att konvertera EPUB till DOCM i två enkla steg. För det första kan du använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API för att konvertera EPUB-filformat till DOC. För det andra, genom att använda avancerad Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), kan du exportera DOC till DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att rendera EPUB till DOCM" %}}
1. Öppna EPUB-filen med klassreferens [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konvertera EPUB till DOC genom att använda medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Ladda DOC-filen med hjälp av [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens för Aspose.Words API
4. Spara dokumentet i DOCM-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Docm
wordDoc->Save(u"output.Docm");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra lösenord för EPUB-dokument via C++" %}}
I processen att rendera EPUB till DOCM kan du öppna en lösenordsskyddad EPUB och även ändra dess lösenord. För att ändra lösenordet för en EPUB-fil måste du känna till ägarlösenordet för det dokumentet. Du kan ladda lösenordsskyddade PDF-dokument med [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) genom att ange dess ägarlösenord och använda ChangePasswords-metoden för att ändra lösenordet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa DOCM-filredigering via C++" %}}
Du kan också begränsa redigering av DOCM-filer genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. API låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Följande kodexempel visar hur man begränsar redigering i ett dokument så att endast redigering i formulärfält är möjlig.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Docm");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-odt/" name="EPUB Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-pcl/" name="EPUB Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-mhtml/" name="EPUB Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-xamlflow/" name="EPUB Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-dotx/" name="EPUB Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-markdown/" name="EPUB Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-wordml/" name="EPUB Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-ott/" name="EPUB Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-dot/" name="EPUB Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-flatopc/" name="EPUB Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-dotm/" name="EPUB Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-ps/" name="EPUB Till PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}