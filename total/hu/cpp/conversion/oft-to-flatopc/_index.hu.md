---
title: Exportálja az OFT-t FLATOPC-be C++-on keresztül
description: C++ API az OFT FLATOPC-vé konvertálásához Microsoft Word vagy Outlook használata nélkül
url: /hu/cpp/conversion/oft-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: FLATOPC
otherformats: DOCX DOCM PNG BMP DOTM PS EPUB TIFF ODT EMF DOC JPEG OTT RTF SVG MD PCL XPS PDF DOT TEXT GIF WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API az OFT exportálásához FLATOPC-be" h2="Alakítsa át az OFT-t FLATOPC-vé a C++ alkalmazáson belül Microsoft Word vagy Outlook nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön C++ fejlesztő, aki e-mail-konverziós funkciókat szeretne hozzáadni alkalmazásaihoz? Az [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) használatával konvertálhatja az OFT fájlformátumot HTML-re. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával exportálhatja a HTML-t FLATOPC-be. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API az OFT FLATOPC-vé konvertálásához" %}}
1. Nyissa meg az OFT fájlt a [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) osztályhivatkozás használatával
2. Alakítsa át az OFT-t HTML-vé a [Mentés](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) tagfüggvény használatával
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot FLATOPC formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal, és állítsa be a Flatopc-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing FlatOpc as save format
doc->Save(u"convertedFile.FlatOpc");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Elemezze az OFT fájlt C++ segítségével" %}}
Nemcsak OFT-jét konvertálhatja FLATOPC-vé, hanem olvashatja, kezelheti és elemzi az OFT dokumentumot. Az [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API MapiMessage osztályával az e-mail tárgyára, címére, törzsére és címzettjére vonatkozó információkat kaphat. Például a get_SenderOftAddress() tulajdonság használatával ellenőrizheti, hogy van-e egy adott feladó e-mail a konverzióhoz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API a FLATOPC fájlformátum szerkesztésének korlátozásához" %}}
Dokumentumvédelmi funkciókat is hozzáadhat az alkalmazáshoz, miközben exportálja a dokumentumot a OFT címről a FLATOPC-be. A védelem hozzáadása a dokumentumhoz egy egyszerű folyamat, hiszen mindössze a védelmi módszert kell alkalmaznia a dokumentumra. A védelem típusát ReadOnly értékre állíthatja, hogy korlátozza a felhasználót a dokumentum szerkesztésében.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.FlatOpc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-docx/" name="OFT Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-docm/" name="OFT Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-png/" name="OFT Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-flatopc/" name="OFT Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-dotm/" name="OFT Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-ps/" name="OFT Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-epub/" name="OFT Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-tiff/" name="OFT Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-odt/" name="OFT Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-emf/" name="OFT Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-doc/" name="OFT Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-jpeg/" name="OFT Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-ott/" name="OFT Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-rtf/" name="OFT Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-svg/" name="OFT Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-md/" name="OFT Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-pcl/" name="OFT Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-xps/" name="OFT Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-pdf/" name="OFT Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-dot/" name="OFT Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-text/" name="OFT Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-gif/" name="OFT Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-wordml/" name="OFT Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/oft-to-dotx/" name="OFT Nak nek DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}