---
title: Esporta EMAIL in DOTM tramite C++
description: API C++ per convertire EMAIL in DOTM senza utilizzare Microsoft Word o Outlook
url: /it/cpp/conversion/email-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOTM
otherformats: JPEG WORDML RTF TIFF BMP OTT TEXT SVG ODT EPUB DOT DOCM EMF GIF PS MD DOCX FLATOPC PCL DOTX PNG DOC PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare EMAIL in DOTM" h2="Trasforma EMAIL in DOTM all'interno dell'applicazione C++ senza richiedere Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere funzionalità di conversione e-mail all'interno delle tue applicazioni? Usando [Aspose.Email for C++](https://products.aspose.com/email/cpp/) puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare HTML in DOTM. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire EMAIL in DOTM" %}}
1. Aprire il file EMAIL utilizzando il riferimento alla classe [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)
2. Converti EMAIL in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato DOTM utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e impostare Dotm come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotm as save format
doc->Save(u"convertedFile.Dotm");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EMAIL tramite C++" %}}
Non solo puoi convertire la tua EMAIL in DOTM, ma puoi leggere, manipolare e analizzare il documento EMAIL. È possibile ottenere informazioni su oggetto, indirizzo, corpo e destinatari dell'e-mail utilizzando la classe MapiMessage dell'API [Aspose.Email for C++](https://products.aspose.com/email/cpp/). Ad esempio, puoi verificare la presenza di un'e-mail del mittente specifica per la conversione utilizzando la proprietà get_SenderEmailAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ per limitare la modifica del formato file DOTM" %}}
Puoi anche aggiungere funzionalità di protezione dei documenti nella tua app durante l'esportazione del documento da EMAIL a DOTM. L'aggiunta della protezione al tuo documento è un processo semplice, poiché tutto ciò che devi fare è applicare il metodo di protezione al tuo documento. È possibile impostare il tipo di protezione su Sola lettura per limitare la modifica del documento da parte dell'utente.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotm");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-jpeg/" name="MSG Per JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-wordml/" name="MSG Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-rtf/" name="MSG Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-tiff/" name="MSG Per TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-dotm/" name="MSG Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-ott/" name="MSG Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-text/" name="MSG Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-svg/" name="MSG Per SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-odt/" name="MSG Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-epub/" name="MSG Per EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-dot/" name="MSG Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-docm/" name="MSG Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-emf/" name="MSG Per EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-gif/" name="MSG Per GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-ps/" name="MSG Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-md/" name="MSG Per MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-docx/" name="MSG Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-flatopc/" name="MSG Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-pcl/" name="MSG Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-dotx/" name="MSG Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-png/" name="MSG Per PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-doc/" name="MSG Per DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-pdf/" name="MSG Per PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/msg-to-xps/" name="MSG Per XPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}