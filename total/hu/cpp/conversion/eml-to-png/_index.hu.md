---
title: Exportálja az EML-t PNG-be C++-on keresztül
description: C++ API az EML PNG-vé konvertálásához Microsoft Word vagy Outlook használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: DOTM XPS PS FLATOPC PCL SVG DOT TIFF BMP PDF EPUB OTT DOCM MD GIF EMF RTF DOC WORDML TEXT DOTX DOCX JPEG ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API az EML exportálásához PNG-be" h2="Alakítsa át az EML-t PNG-vé a C++ alkalmazáson belül Microsoft Word vagy Outlook nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön C++ fejlesztő, aki e-mail-konverziós funkciókat szeretne hozzáadni alkalmazásaihoz? Az [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) használatával konvertálhatja az EML fájlformátumot HTML-re. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával exportálhatja a HTML-t PNG-be. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API az EML PNG-vé konvertálásához" %}}
1. Nyissa meg az EML fájlt a [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) osztályhivatkozás használatával
2. Alakítsa át az EML-t HTML-vé a [Mentés](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) tagfüggvény használatával
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot PNG formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal, és állítsa be a Png-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Elemezze az EML fájlt C++ segítségével" %}}
Nemcsak EML-jét konvertálhatja PNG-vé, hanem olvashatja, kezelheti és elemzi az EML dokumentumot. Az [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API MapiMessage osztályával az e-mail tárgyára, címére, törzsére és címzettjére vonatkozó információkat kaphat. Például a get_SenderEmlAddress() tulajdonság használatával ellenőrizheti, hogy van-e egy adott feladó e-mail a konverzióhoz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API a PNG fájlformátum szerkesztésének korlátozásához" %}}
Dokumentumvédelmi funkciókat is hozzáadhat az alkalmazáshoz, miközben exportálja a dokumentumot a EML címről a PNG-be. A védelem hozzáadása a dokumentumhoz egy egyszerű folyamat, hiszen mindössze a védelmi módszert kell alkalmaznia a dokumentumra. A védelem típusát ReadOnly értékre állíthatja, hogy korlátozza a felhasználót a dokumentum szerkesztésében.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-dotm/" name="EML Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-xps/" name="EML Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-ps/" name="EML Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-flatopc/" name="EML Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-pcl/" name="EML Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-svg/" name="EML Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-dot/" name="EML Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-tiff/" name="EML Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-png/" name="EML Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-pdf/" name="EML Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-epub/" name="EML Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-ott/" name="EML Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-docm/" name="EML Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-md/" name="EML Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-gif/" name="EML Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-emf/" name="EML Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-rtf/" name="EML Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-doc/" name="EML Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-wordml/" name="EML Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-text/" name="EML Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-dotx/" name="EML Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-docx/" name="EML Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-jpeg/" name="EML Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/eml-to-odt/" name="EML Nak nek ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}