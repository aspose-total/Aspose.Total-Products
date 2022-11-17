---
title: API C++ per convertire PDF in PPS
description: Converti PDF in PPS tramite C++ senza utilizzare Microsoft Word o Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: PPS
otherformats: PPT SWF PPSM POT PPTM XAML OTP POTX POTM ODP POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da PDF a PPS all'interno di applicazioni C++" h2="Converti PDF in PPS all'interno delle tue applicazioni C++ senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sei uno sviluppatore C++ e stai cercando di aggiungere per integrare la funzionalità di conversione da PDF a PPS all'interno delle tue applicazioni C++? Puoi farlo in due semplici passaggi. È possibile esportare PDF in PPTX utilizzando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). In secondo luogo, utilizzando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), puoi convertire PPTX in PPS. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per esportare PDF in PPS" %}}
1. Aprire il file PDF utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converti PDF in PPTX utilizzando la funzione del metodo [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Caricare il documento PPTX utilizzando [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) riferimento alla classe
4. Salvare il documento in formato PPS utilizzando la funzione membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e impostare `Pps` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pdf");
// save PDF as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pps format
prs->Save(u"output.pps", Aspose::Slides::Export::SaveFormat::Pps);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Modifica la password del documento PDF tramite C++" %}}
Nel processo di rendering da PDF a PPS, puoi aprire un PDF protetto da password e anche cambiarne la password. Per modificare la password di un file PDF, è necessario conoscere la password del proprietario di quel documento. È possibile caricare un documento PDF protetto da password con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) specificando la password del proprietario e utilizzare il metodo ChangePasswords per modificare la password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi immagini dal Web in file PPS tramite C++" %}}
Dopo aver convertito PDF in PPS, puoi anche aggiungere immagini dal Web al documento di output. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supporta operazioni con immagini in questi formati popolari: JPEG, PNG, BMP, GIF e altri. Puoi aggiungere una o più immagini sul tuo computer a una diapositiva in una presentazione. Questo codice di esempio in C++ mostra come aggiungere un'immagine a un file PPS
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPS file
auto pres = System::MakeObject<Presentation>("output.pps");
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
pres->Save(u"updated.pps", SaveFormat::Pps);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-ppt/" name="PDF Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-swf/" name="PDF Per SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-ppsm/" name="PDF Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-pot/" name="PDF Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-pptm/" name="PDF Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-xaml/" name="PDF Per XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-otp/" name="PDF Per OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-potx/" name="PDF Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-potm/" name="PDF Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-pps/" name="PDF Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-powerpoint/" name="PDF Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pdf-to-ppsx/" name="PDF Per PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}