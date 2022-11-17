---
title: C++ API do eksportu TEX do XAMLFLOW
description: Konwertuj TEX na XAMLFLOW w aplikacjach C++.

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XAMLFLOW
otherformats: PCL ODT DOTM MHTML DOT PS FLATOPC MARKDOWN OTT WORDML DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu TEX do XAMLFLOW" h2="Renderuj TEX do XAMLFLOW w aplikacjach C++ bez konieczności korzystania z aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Biblioteki automatyzacji formatu plików [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umożliwiają programistom C++ konwersję TEX do XAMLFLOW w dwóch prostych krokach. Po pierwsze, możesz użyć API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), aby przekonwertować format pliku TEX na DOC. Po drugie, korzystając z zaawansowanego interfejsu API przetwarzania dokumentów Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz wyeksportować DOC do XAMLFLOW. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do renderowania TEX do XAMLFLOW" %}}
1. Otwórz plik TEX, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj TEX na DOC za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Załaduj plik DOC, używając odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API
4. Zapisz dokument w formacie XAMLFLOW za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Xamlflow
wordDoc->Save(u"output.Xamlflow");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Zmień hasło dokumentu TEX za pomocą C++" %}}
W procesie renderowania TEX do XAMLFLOW możesz otworzyć TEX chroniony hasłem, a także zmienić jego hasło. Aby zmienić hasło do pliku TEX, musisz znać hasło właściciela tego dokumentu. Możesz załadować dokument PDF chroniony hasłem za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), określając hasło właściciela i używając metody ChangePasswords, aby zmienić hasło.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-pcl/" name="TEX Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-odt/" name="TEX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-dotm/" name="TEX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-mhtml/" name="TEX Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-dot/" name="TEX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-ps/" name="TEX Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-flatopc/" name="TEX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-markdown/" name="TEX Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-ott/" name="TEX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-wordml/" name="TEX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-dotx/" name="TEX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tex-to-rtf/" name="TEX Do RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}