---
title: C++ API do eksportu PCL do DOCM
description: Konwertuj PCL na DOCM w aplikacjach C++.

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: DOCM
otherformats: DOT FLATOPC MHTML MARKDOWN XAMLFLOW DOTM DOTX OTT PS RTF WORDML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu PCL do DOCM" h2="Renderuj PCL do DOCM w aplikacjach C++ bez konieczności korzystania z aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Biblioteki automatyzacji formatu plików [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umożliwiają programistom C++ konwersję PCL do DOCM w dwóch prostych krokach. Po pierwsze, możesz użyć API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), aby przekonwertować format pliku PCL na DOC. Po drugie, korzystając z zaawansowanego interfejsu API przetwarzania dokumentów Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz wyeksportować DOC do DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do renderowania PCL do DOCM" %}}
1. Otwórz plik PCL, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj PCL na DOC za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Załaduj plik DOC, używając odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API
4. Zapisz dokument w formacie DOCM za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Docm
wordDoc->Save(u"output.Docm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Zmień hasło dokumentu PCL za pomocą C++" %}}
W procesie renderowania PCL do DOCM możesz otworzyć PCL chroniony hasłem, a także zmienić jego hasło. Aby zmienić hasło do pliku PCL, musisz znać hasło właściciela tego dokumentu. Możesz załadować dokument PDF chroniony hasłem za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), określając hasło właściciela i używając metody ChangePasswords, aby zmienić hasło.
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

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję plików DOCM za pomocą C++" %}}
Możesz też ograniczyć edycję plików DOCM za pomocą interfejsu API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Czasami może być konieczne ograniczenie możliwości edytowania dokumentu i zezwolenie tylko na określone czynności. Interfejs API umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Poniższy przykład kodu demonstruje, jak ograniczyć edycję w dokumencie, dzięki czemu możliwa jest tylko edycja w polach formularza.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Docm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-dot/" name="PCL Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-flatopc/" name="PCL Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-mhtml/" name="PCL Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-markdown/" name="PCL Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-xamlflow/" name="PCL Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-dotm/" name="PCL Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-dotx/" name="PCL Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-ott/" name="PCL Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-ps/" name="PCL Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-rtf/" name="PCL Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-wordml/" name="PCL Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pcl-to-odt/" name="PCL Do ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}