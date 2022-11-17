---
title: API C++ per convertire XSLFO in POWERPOINT
description: Converti XSLFO in POWERPOINT tramite C++ senza utilizzare Microsoft Word o Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: SWF POT PPT POTM PPTM PPS PPSM ODP POTX XAML PPSX OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da XSLFO a POWERPOINT all'interno di applicazioni C++" h2="Converti XSLFO in POWERPOINT all'interno delle tue applicazioni C++ senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere per integrare la funzionalità di conversione da XSLFO a POWERPOINT all'interno delle tue applicazioni C++? Puoi farlo in due semplici passaggi. È possibile esportare XSLFO in PPTX utilizzando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). In secondo luogo, utilizzando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), puoi convertire PPTX in POWERPOINT. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per esportare XSLFO in POWERPOINT" %}}
1. Aprire il file XSLFO utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converti XSLFO in PPTX utilizzando la funzione del metodo [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Caricare il documento PPTX utilizzando [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) riferimento alla classe
4. Salvare il documento in formato POWERPOINT utilizzando la funzione membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e impostare `Powerpoint` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Modifica la password del documento XSLFO tramite C++" %}}
Nel processo di rendering da XSLFO a POWERPOINT, puoi aprire un XSLFO protetto da password e anche cambiarne la password. Per modificare la password di un file XSLFO, è necessario conoscere la password del proprietario di quel documento. È possibile caricare un documento PDF protetto da password con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) specificando la password del proprietario e utilizzare il metodo ChangePasswords per modificare la password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi immagini dal Web in file POWERPOINT tramite C++" %}}
Dopo aver convertito XSLFO in POWERPOINT, puoi anche aggiungere immagini dal Web al documento di output. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supporta operazioni con immagini in questi formati popolari: JPEG, PNG, BMP, GIF e altri. Puoi aggiungere una o più immagini sul tuo computer a una diapositiva in una presentazione. Questo codice di esempio in C++ mostra come aggiungere un'immagine a un file POWERPOINT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-swf/" name="XSLFO Per SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-pot/" name="XSLFO Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-ppt/" name="XSLFO Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-potm/" name="XSLFO Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-pptm/" name="XSLFO Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-pps/" name="XSLFO Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-ppsm/" name="XSLFO Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-powerpoint/" name="XSLFO Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-potx/" name="XSLFO Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-xaml/" name="XSLFO Per XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-ppsx/" name="XSLFO Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/xslfo-to-otp/" name="XSLFO Per OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}