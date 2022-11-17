---
title: C++ API do eksportu XPS do XAMLFLOW
description: Konwertuj XPS na XAMLFLOW w aplikacjach C++.

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: XAMLFLOW
otherformats: OTT RTF DOT MHTML WORDML DOTX DOCM PS FLATOPC ODT DOTM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu XPS do XAMLFLOW" h2="Renderuj XPS do XAMLFLOW w aplikacjach C++ bez konieczności korzystania z aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Biblioteki automatyzacji formatu plików [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umożliwiają programistom C++ konwersję XPS do XAMLFLOW w dwóch prostych krokach. Po pierwsze, możesz użyć API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), aby przekonwertować format pliku XPS na DOC. Po drugie, korzystając z zaawansowanego interfejsu API przetwarzania dokumentów Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz wyeksportować DOC do XAMLFLOW. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do renderowania XPS do XAMLFLOW" %}}
1. Otwórz plik XPS, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj XPS na DOC za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Załaduj plik DOC, używając odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API
4. Zapisz dokument w formacie XAMLFLOW za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Xamlflow
wordDoc->Save(u"output.Xamlflow");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Zmień hasło dokumentu XPS za pomocą C++" %}}
W procesie renderowania XPS do XAMLFLOW możesz otworzyć XPS chroniony hasłem, a także zmienić jego hasło. Aby zmienić hasło do pliku XPS, musisz znać hasło właściciela tego dokumentu. Możesz załadować dokument PDF chroniony hasłem za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), określając hasło właściciela i używając metody ChangePasswords, aby zmienić hasło.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję plików XAMLFLOW za pomocą C++" %}}
Możesz też ograniczyć edycję plików XAMLFLOW za pomocą interfejsu API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Czasami może być konieczne ograniczenie możliwości edytowania dokumentu i zezwolenie tylko na określone czynności. Interfejs API umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Poniższy przykład kodu demonstruje, jak ograniczyć edycję w dokumencie, dzięki czemu możliwa jest tylko edycja w polach formularza.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Xamlflow");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-ott/" name="XPS Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-rtf/" name="XPS Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-dot/" name="XPS Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-mhtml/" name="XPS Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-wordml/" name="XPS Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-dotx/" name="XPS Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-xamlflow/" name="XPS Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-ps/" name="XPS Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-flatopc/" name="XPS Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-odt/" name="XPS Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-dotm/" name="XPS Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-pcl/" name="XPS Do PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}