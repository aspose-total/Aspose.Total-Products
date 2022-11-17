---
title: Esporta OFT in GIF tramite C++
description: API C++ per convertire OFT in GIF senza utilizzare Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: GIF
otherformats: PDF PNG TIFF XPS SVG PCL JPEG DOTX DOT DOC WORDML BMP RTF FLATOPC OTT MD DOTM ODT EMF DOCM TEXT PS EPUB DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare OFT in GIF" h2="Trasforma OFT in GIF all'interno dell'applicazione C++ senza richiedere Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere funzionalità di conversione e-mail all'interno delle tue applicazioni? Usando [Aspose.Oft per C++](https://products.aspose.com/oft/cpp/) puoi convertire il formato del file OFT in HTML. Successivamente, utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare HTML in GIF. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire OFT in GIF" %}}
1. Aprire il file OFT utilizzando il riferimento alla classe [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Converti OFT in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato GIF utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e impostare Gif come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Gif as save format
doc->Save(u"convertedFile.Gif");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file OFT tramite C++" %}}
Non solo puoi convertire la tua OFT in GIF, ma puoi leggere, manipolare e analizzare il documento OFT. È possibile ottenere informazioni su oggetto, indirizzo, corpo e destinatari dell'e-mail utilizzando la classe MapiMessage dell'API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Ad esempio, puoi verificare la presenza di un'e-mail del mittente specifica per la conversione utilizzando la proprietà get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ per limitare la modifica del formato file GIF" %}}
Puoi anche aggiungere funzionalità di protezione dei documenti nella tua app durante l'esportazione del documento da OFT a GIF. L'aggiunta della protezione al tuo documento è un processo semplice, poiché tutto ciò che devi fare è applicare il metodo di protezione al tuo documento. È possibile impostare il tipo di protezione su Sola lettura per limitare la modifica del documento da parte dell'utente.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Gif");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-pdf/" name="OFT Per PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-png/" name="OFT Per PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-tiff/" name="OFT Per TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-xps/" name="OFT Per XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-svg/" name="OFT Per SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-pcl/" name="OFT Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-jpeg/" name="OFT Per JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-dotx/" name="OFT Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-dot/" name="OFT Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-doc/" name="OFT Per DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-wordml/" name="OFT Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-gif/" name="OFT Per GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-rtf/" name="OFT Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-flatopc/" name="OFT Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-ott/" name="OFT Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-md/" name="OFT Per MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-dotm/" name="OFT Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-odt/" name="OFT Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-emf/" name="OFT Per EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-docm/" name="OFT Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-text/" name="OFT Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-ps/" name="OFT Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-epub/" name="OFT Per EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/oft-to-docx/" name="OFT Per DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}