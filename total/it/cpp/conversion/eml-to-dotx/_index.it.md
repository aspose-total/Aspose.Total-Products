---
title: Esporta EML in DOTX tramite C++
description: API C++ per convertire EML in DOTX senza utilizzare Microsoft Word o Outlook
url: /it/cpp/conversion/eml-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOTX
otherformats: BMP GIF EMF PDF JPEG PNG ODT TIFF DOTM PS DOC DOT MD FLATOPC TEXT RTF DOCX PCL DOCM WORDML OTT EPUB XPS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare EML in DOTX" h2="Trasforma EML in DOTX all'interno dell'applicazione C++ senza richiedere Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere funzionalità di conversione e-mail all'interno delle tue applicazioni? Usando [Aspose.Eml per C++](https://products.aspose.com/eml/cpp/) puoi convertire il formato del file EML in HTML. Successivamente, utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare HTML in DOTX. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire EML in DOTX" %}}
1. Aprire il file EML utilizzando il riferimento alla classe [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Converti EML in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato DOTX utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e impostare Dotx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotx as save format
doc->Save(u"convertedFile.Dotx");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EML tramite C++" %}}
Non solo puoi convertire la tua EML in DOTX, ma puoi leggere, manipolare e analizzare il documento EML. È possibile ottenere informazioni su oggetto, indirizzo, corpo e destinatari dell'e-mail utilizzando la classe MapiMessage dell'API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Ad esempio, puoi verificare la presenza di un'e-mail del mittente specifica per la conversione utilizzando la proprietà get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ per limitare la modifica del formato file DOTX" %}}
Puoi anche aggiungere funzionalità di protezione dei documenti nella tua app durante l'esportazione del documento da EML a DOTX. L'aggiunta della protezione al tuo documento è un processo semplice, poiché tutto ciò che devi fare è applicare il metodo di protezione al tuo documento. È possibile impostare il tipo di protezione su Sola lettura per limitare la modifica del documento da parte dell'utente.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotx");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-dotx/" name="EML Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-gif/" name="EML Per GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-emf/" name="EML Per EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-pdf/" name="EML Per PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-jpeg/" name="EML Per JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-png/" name="EML Per PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-odt/" name="EML Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-tiff/" name="EML Per TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-dotm/" name="EML Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-ps/" name="EML Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-doc/" name="EML Per DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-dot/" name="EML Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-md/" name="EML Per MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-flatopc/" name="EML Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-text/" name="EML Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-rtf/" name="EML Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-docx/" name="EML Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-pcl/" name="EML Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-docm/" name="EML Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-wordml/" name="EML Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-ott/" name="EML Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-epub/" name="EML Per EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-xps/" name="EML Per XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/eml-to-svg/" name="EML Per SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}