---
title: API C++ per esportare TEX in WORDML
description: Converti TEX in WORDML all'interno di applicazioni C++.
url: /it/cpp/conversion/tex-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: WORDML
otherformats: DOT DOTM PCL MARKDOWN DOCM FLATOPC ODT PS XAMLFLOW DOTX OTT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per esportare TEX in WORDML" h2="Esegui il rendering da TEX a WORDML all'interno di applicazioni C++ senza richiedere alcuna applicazione di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Le librerie di automazione dei formati di file [Aspose.Total for C++](https://products.aspose.com/total/cpp/) consentono agli sviluppatori C++ di convertire TEX in WORDML in due semplici passaggi. Innanzitutto, puoi utilizzare l'API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) per convertire il formato di file TEX in DOC. In secondo luogo, utilizzando l'API avanzata di elaborazione dei documenti di Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare DOC in WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per il rendering di TEX in WORDML" %}}
1. Aprire il file TEX utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converti TEX in DOC utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Caricare il file DOC utilizzando il riferimento alla classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dell'API Aspose.Words
4. Salvare il documento in formato WORDML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as WordML
wordDoc->Save(u"output.WordML");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Modifica la password del documento TEX tramite C++" %}}
Nel processo di rendering da TEX a WORDML, puoi aprire un TEX protetto da password e anche cambiarne la password. Per modificare la password di un file TEX, è necessario conoscere la password del proprietario di quel documento. È possibile caricare un documento PDF protetto da password con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) specificando la password del proprietario e utilizzare il metodo ChangePasswords per modificare la password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei file WORDML tramite C++" %}}
Puoi anche limitare la modifica dei file WORDML utilizzando l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. L'API consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Nell'esempio di codice seguente viene illustrato come limitare la modifica in un documento in modo che sia possibile solo la modifica nei campi modulo.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.WordML");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-dot/" name="TEX Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-dotm/" name="TEX Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-pcl/" name="TEX Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-markdown/" name="TEX Per MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-wordml/" name="TEX Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-flatopc/" name="TEX Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-odt/" name="TEX Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-ps/" name="TEX Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-xamlflow/" name="TEX Per XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-dotx/" name="TEX Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-ott/" name="TEX Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/tex-to-rtf/" name="TEX Per RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}