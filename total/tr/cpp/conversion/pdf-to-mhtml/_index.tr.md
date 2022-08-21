---
title: PDF'yi MHTML'ye Dışa Aktarmak için C++ API
description: C++ uygulamaları içinde PDF'yi MHTML'ye dönüştürün.
url: /tr/cpp/conversion/pdf-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: MHTML
otherformats: ODT WORDML XAMLFLOW FLATOPC DOTM OTT DOTX MARKDOWN RTF PS DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PDF'yi MHTML'ye Dışa Aktarmak için C++ API" h2="Herhangi bir üçüncü taraf uygulaması gerektirmeden C++ uygulamaları içinde PDF'den MHTML'ye işleyin" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) dosya formatı otomasyon kitaplıkları, C++ geliştiricisinin PDF'yi iki basit adımda MHTML'ye dönüştürmesine olanak tanır. İlk olarak, PDF dosya biçimini DOC'ye dönüştürmek için [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API'sini kullanabilirsiniz. İkinci olarak, gelişmiş Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak DOC'yi MHTML'ye aktarabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF'yi MHTML'ye Oluşturmak için C++ API'si" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak PDF dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) üye işlevini kullanarak PDF'yi DOC'ye dönüştürün
3. Aspose.Words API'sinin [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak DOC dosyasını yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) üye işlevini kullanarak belgeyi MHTML biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="PDF Belgesinin Şifresini C++ ile Değiştirin" %}}
PDF'yi MHTML'ye oluşturma sürecinde, parola korumalı bir PDF açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir PDF dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
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

{{% blocks/products/pf/feature-page-section  h2="MHTML Dosya Düzenlemesini C++ ile Kısıtla" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak MHTML dosya düzenlemesini de kısıtlayabilirsiniz. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli eylemlere izin vermeniz gerekebilir. API, [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod örneği, yalnızca form alanlarında düzenleme yapılabilmesi için bir belgede düzenlemenin nasıl kısıtlanacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-odt/" name="PDF İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-wordml/" name="PDF İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-xamlflow/" name="PDF İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-flatopc/" name="PDF İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-dotm/" name="PDF İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-ott/" name="PDF İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-dotx/" name="PDF İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-markdown/" name="PDF İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-rtf/" name="PDF İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-ps/" name="PDF İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-dot/" name="PDF İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pdf-to-mhtml/" name="PDF İle MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}