---
title: API C++ per esportare PCL in ODT
description: Converti PCL in ODT all'interno di applicazioni C++.

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: ODT
otherformats: MARKDOWN MHTML DOT RTF FLATOPC OTT DOTM PS DOTX WORDML XAMLFLOW DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare PCL in ODT" h2="Esegui il rendering da PCL a ODT all'interno di applicazioni C++ senza richiedere alcuna applicazione di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Le librerie di automazione dei formati di file [Aspose.Total for C++](https://products.aspose.com/total/cpp/) consentono agli sviluppatori C++ di convertire PCL in ODT in due semplici passaggi. Innanzitutto, puoi utilizzare l'API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) per convertire il formato di file PCL in DOC. In secondo luogo, utilizzando l'API avanzata di elaborazione dei documenti di Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare DOC in ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per il rendering di PCL in ODT" %}}
1. Aprire il file PCL utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converti PCL in DOC utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Caricare il file DOC utilizzando il riferimento alla classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dell'API Aspose.Words
4. Salvare il documento in formato ODT utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Odt
wordDoc->Save(u"output.Odt");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Modifica la password del documento PCL tramite C++" %}}
Nel processo di rendering da PCL a ODT, puoi aprire un PCL protetto da password e anche cambiarne la password. Per modificare la password di un file PCL, è necessario conoscere la password del proprietario di quel documento. È possibile caricare un documento PDF protetto da password con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) specificando la password del proprietario e utilizzare il metodo ChangePasswords per modificare la password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei file ODT tramite C++" %}}
Puoi anche limitare la modifica dei file ODT utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. L'API consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Nell'esempio di codice seguente viene illustrato come limitare la modifica in un documento in modo che sia possibile solo la modifica nei campi modulo.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Odt");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-markdown/" name="PCL Per MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-mhtml/" name="PCL Per MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-dot/" name="PCL Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-rtf/" name="PCL Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-flatopc/" name="PCL Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-ott/" name="PCL Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-dotm/" name="PCL Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-ps/" name="PCL Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-dotx/" name="PCL Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-wordml/" name="PCL Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xamlflow/" name="PCL Per XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-odt/" name="PCL Per ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}