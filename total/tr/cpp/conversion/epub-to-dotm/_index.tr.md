---
title: EPUB'yi DOTM'ye Dışa Aktarmak için C++ API
description: C++ uygulamaları içinde EPUB'yi DOTM'ye dönüştürün.
url: /tr/cpp/conversion/epub-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: DOTM
otherformats: DOCM RTF OTT DOT MARKDOWN ODT MHTML PS WORDML XAMLFLOW DOTX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EPUB'yi DOTM'ye Dışa Aktarmak için C++ API" h2="Herhangi bir üçüncü taraf uygulaması gerektirmeden C++ uygulamaları içinde EPUB'den DOTM'ye işleyin" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) dosya formatı otomasyon kitaplıkları, C++ geliştiricisinin EPUB'yi iki basit adımda DOTM'ye dönüştürmesine olanak tanır. İlk olarak, EPUB dosya biçimini DOC'ye dönüştürmek için [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API'sini kullanabilirsiniz. İkinci olarak, gelişmiş Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak DOC'yi DOTM'ye aktarabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB'yi DOTM'ye Oluşturmak için C++ API'si" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak EPUB dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) üye işlevini kullanarak EPUB'yi DOC'ye dönüştürün
3. Aspose.Words API'sinin [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak DOC dosyasını yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) üye işlevini kullanarak belgeyi DOTM biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotm
wordDoc->Save(u"output.Dotm");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="EPUB Belgesinin Şifresini C++ ile Değiştirin" %}}
EPUB'yi DOTM'ye oluşturma sürecinde, parola korumalı bir EPUB açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir EPUB dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
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

{{% blocks/products/pf/feature-page-section  h2="DOTM Dosya Düzenlemesini C++ ile Kısıtla" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak DOTM dosya düzenlemesini de kısıtlayabilirsiniz. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli eylemlere izin vermeniz gerekebilir. API, [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod örneği, yalnızca form alanlarında düzenleme yapılabilmesi için bir belgede düzenlemenin nasıl kısıtlanacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotm");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-dotm/" name="EPUB İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-rtf/" name="EPUB İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-ott/" name="EPUB İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-dot/" name="EPUB İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-markdown/" name="EPUB İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-odt/" name="EPUB İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-mhtml/" name="EPUB İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-ps/" name="EPUB İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-wordml/" name="EPUB İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-xamlflow/" name="EPUB İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-dotx/" name="EPUB İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/epub-to-flatopc/" name="EPUB İle FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}