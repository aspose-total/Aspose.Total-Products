---
title: C++ API do eksportu EPUB do GIF
description: Konwertuj EPUB na GIF w aplikacjach C++.
url: /pl/cpp/conversion/epub-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: GIF
otherformats: DOT MARKDOWN OTT DOTX DOTM MHTML ODT PCL WORDML XAMLFLOW PS FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu EPUB do GIF" h2="Renderuj EPUB do GIF w aplikacjach C++ bez konieczności korzystania z aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Biblioteki automatyzacji formatu plików [Aspose.Total for C++](https://products.aspose.com/total/cpp/) umożliwiają programistom C++ konwersję EPUB do GIF w dwóch prostych krokach. Po pierwsze, możesz użyć API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), aby przekonwertować format pliku EPUB na DOC. Po drugie, korzystając z zaawansowanego interfejsu API przetwarzania dokumentów Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz wyeksportować DOC do GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do renderowania EPUB do GIF" %}}
1. Otwórz plik EPUB, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj EPUB na DOC za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Załaduj plik DOC, używając odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API
4. Zapisz dokument w formacie GIF za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Gif
wordDoc->Save(u"output.Gif");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Zmień hasło dokumentu EPUB za pomocą C++" %}}
W procesie renderowania EPUB do GIF możesz otworzyć EPUB chroniony hasłem, a także zmienić jego hasło. Aby zmienić hasło do pliku EPUB, musisz znać hasło właściciela tego dokumentu. Możesz załadować dokument PDF chroniony hasłem za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), określając hasło właściciela i używając metody ChangePasswords, aby zmienić hasło.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję plików GIF za pomocą C++" %}}
Możesz też ograniczyć edycję plików GIF za pomocą interfejsu API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Czasami może być konieczne ograniczenie możliwości edytowania dokumentu i zezwolenie tylko na określone czynności. Interfejs API umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Poniższy przykład kodu demonstruje, jak ograniczyć edycję w dokumencie, dzięki czemu możliwa jest tylko edycja w polach formularza.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Gif");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-dot/" name="EPUB Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-markdown/" name="EPUB Do MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-ott/" name="EPUB Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-dotx/" name="EPUB Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-dotm/" name="EPUB Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-mhtml/" name="EPUB Do MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-odt/" name="EPUB Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-pcl/" name="EPUB Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-wordml/" name="EPUB Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-xamlflow/" name="EPUB Do XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-ps/" name="EPUB Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/epub-to-flatopc/" name="EPUB Do FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}