---
title: Exportálja az MSG-t OTT-be C++-on keresztül
description: C++ API az MSG OTT-vé konvertálásához Microsoft Word vagy Outlook használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: OTT
otherformats: DOTM DOC PNG SVG PS TEXT BMP RTF DOTX EMF MD GIF FLATOPC XPS DOT DOCX EPUB ODT WORDML PDF PCL TIFF DOCM JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API az MSG exportálásához OTT-be" h2="Alakítsa át az MSG-t OTT-vé a C++ alkalmazáson belül Microsoft Word vagy Outlook nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ön C++ fejlesztő, aki e-mail-konverziós funkciókat szeretne hozzáadni alkalmazásaihoz? Az [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) használatával konvertálhatja az MSG fájlformátumot HTML-re. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API használatával exportálhatja a HTML-t OTT-be. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API az MSG OTT-vé konvertálásához" %}}
1. Nyissa meg az MSG fájlt a [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message) osztályhivatkozás használatával
2. Alakítsa át az MSG-t HTML-vé a [Mentés](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) tagfüggvény használatával
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot OTT formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal, és állítsa be a Ott-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Ott as save format
doc->Save(u"convertedFile.Ott");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Elemezze az MSG fájlt C++ segítségével" %}}
Nemcsak MSG-jét konvertálhatja OTT-vé, hanem olvashatja, kezelheti és elemzi az MSG dokumentumot. Az [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) API MapiMessage osztályával az e-mail tárgyára, címére, törzsére és címzettjére vonatkozó információkat kaphat. Például a get_SenderMsgAddress() tulajdonság használatával ellenőrizheti, hogy van-e egy adott feladó e-mail a konverzióhoz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API a OTT fájlformátum szerkesztésének korlátozásához" %}}
Dokumentumvédelmi funkciókat is hozzáadhat az alkalmazáshoz, miközben exportálja a dokumentumot a MSG címről a OTT-be. A védelem hozzáadása a dokumentumhoz egy egyszerű folyamat, hiszen mindössze a védelmi módszert kell alkalmaznia a dokumentumra. A védelem típusát ReadOnly értékre állíthatja, hogy korlátozza a felhasználót a dokumentum szerkesztésében.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Ott");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-dotm/" name="MSG Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-doc/" name="MSG Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-png/" name="MSG Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-svg/" name="MSG Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-ps/" name="MSG Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-text/" name="MSG Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-ott/" name="MSG Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-rtf/" name="MSG Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-dotx/" name="MSG Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-emf/" name="MSG Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-md/" name="MSG Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-gif/" name="MSG Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-flatopc/" name="MSG Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-xps/" name="MSG Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-dot/" name="MSG Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-docx/" name="MSG Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-epub/" name="MSG Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-odt/" name="MSG Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-wordml/" name="MSG Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-pdf/" name="MSG Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-pcl/" name="MSG Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-tiff/" name="MSG Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-docm/" name="MSG Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/msg-to-jpeg/" name="MSG Nak nek JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}