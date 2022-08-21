---
title: C++ API för att exportera CGM till MHTML
description: Konvertera CGM till MHTML inom C++-applikationer.
url: /sv/cpp/conversion/cgm-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: MHTML
otherformats: RTF OTT MARKDOWN FLATOPC DOTM PS WORDML DOT PCL DOTX XAMLFLOW DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera CGM till MHTML" h2="Återge CGM till MHTML inom C++-applikationer utan att kräva någon tredjepartsapplikation" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) filformatsautomatiseringsbibliotek tillåter C++-utvecklare att konvertera CGM till MHTML i två enkla steg. För det första kan du använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API för att konvertera CGM-filformat till DOC. För det andra, genom att använda avancerad Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), kan du exportera DOC till MHTML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att rendera CGM till MHTML" %}}
1. Öppna CGM-filen med klassreferens [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konvertera CGM till DOC genom att använda medlemsfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Ladda DOC-filen med hjälp av [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens för Aspose.Words API
4. Spara dokumentet i MHTML-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.cgm");
// save CGM as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra lösenord för CGM-dokument via C++" %}}
I processen att rendera CGM till MHTML kan du öppna en lösenordsskyddad CGM och även ändra dess lösenord. För att ändra lösenordet för en CGM-fil måste du känna till ägarlösenordet för det dokumentet. Du kan ladda lösenordsskyddade PDF-dokument med [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) genom att ange dess ägarlösenord och använda ChangePasswords-metoden för att ändra lösenordet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa MHTML-filredigering via C++" %}}
Du kan också begränsa redigering av MHTML-filer genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. API låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Följande kodexempel visar hur man begränsar redigering i ett dokument så att endast redigering i formulärfält är möjlig.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-rtf/" name="CGM Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-ott/" name="CGM Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-markdown/" name="CGM Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-flatopc/" name="CGM Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-dotm/" name="CGM Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-ps/" name="CGM Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-wordml/" name="CGM Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-dot/" name="CGM Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-pcl/" name="CGM Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-dotx/" name="CGM Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-xamlflow/" name="CGM Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/cgm-to-mhtml/" name="CGM Till MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}