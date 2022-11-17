---
title: Esporta EMLX in MD tramite C++
description: API C++ per convertire EMLX in MD senza utilizzare Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: MD
otherformats: DOT XPS EPUB DOCX WORDML JPEG DOCM BMP PNG DOTX PS FLATOPC GIF OTT TIFF EMF PCL ODT SVG DOTM RTF DOC PDF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare EMLX in MD" h2="Trasforma EMLX in MD all'interno dell'applicazione C++ senza richiedere Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere funzionalità di conversione e-mail all'interno delle tue applicazioni? Usando [Aspose.Emlx per C++](https://products.aspose.com/emlx/cpp/) puoi convertire il formato del file EMLX in HTML. Successivamente, utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare HTML in MD. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire EMLX in MD" %}}
1. Aprire il file EMLX utilizzando il riferimento alla classe [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Converti EMLX in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato MD utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e impostare Md come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Md as save format
doc->Save(u"convertedFile.Md");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EMLX tramite C++" %}}
Non solo puoi convertire la tua EMLX in MD, ma puoi leggere, manipolare e analizzare il documento EMLX. È possibile ottenere informazioni su oggetto, indirizzo, corpo e destinatari dell'e-mail utilizzando la classe MapiMessage dell'API [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/). Ad esempio, puoi verificare la presenza di un'e-mail del mittente specifica per la conversione utilizzando la proprietà get_SenderEmlxAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ per limitare la modifica del formato file MD" %}}
Puoi anche aggiungere funzionalità di protezione dei documenti nella tua app durante l'esportazione del documento da EMLX a MD. L'aggiunta della protezione al tuo documento è un processo semplice, poiché tutto ciò che devi fare è applicare il metodo di protezione al tuo documento. È possibile impostare il tipo di protezione su Sola lettura per limitare la modifica del documento da parte dell'utente.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Md");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-dot/" name="EMLX Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-xps/" name="EMLX Per XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-epub/" name="EMLX Per EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-docx/" name="EMLX Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-wordml/" name="EMLX Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-jpeg/" name="EMLX Per JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-docm/" name="EMLX Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-md/" name="EMLX Per MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-png/" name="EMLX Per PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-dotx/" name="EMLX Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-ps/" name="EMLX Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-flatopc/" name="EMLX Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-gif/" name="EMLX Per GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-ott/" name="EMLX Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-tiff/" name="EMLX Per TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-emf/" name="EMLX Per EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-pcl/" name="EMLX Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-odt/" name="EMLX Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-svg/" name="EMLX Per SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-dotm/" name="EMLX Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-rtf/" name="EMLX Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-doc/" name="EMLX Per DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-pdf/" name="EMLX Per PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/emlx-to-text/" name="EMLX Per TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}