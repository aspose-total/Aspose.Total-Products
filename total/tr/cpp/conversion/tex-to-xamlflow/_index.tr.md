---
title: TEX'yi XAMLFLOW'ye Dışa Aktarmak için C++ API
description: C++ uygulamaları içinde TEX'yi XAMLFLOW'ye dönüştürün.
url: /tr/cpp/conversion/tex-to-xamlflow/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XAMLFLOW
otherformats: PCL ODT DOTM MHTML DOT PS FLATOPC MARKDOWN OTT WORDML DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="TEX'yi XAMLFLOW'ye Dışa Aktarmak için C++ API" h2="Herhangi bir üçüncü taraf uygulaması gerektirmeden C++ uygulamaları içinde TEX'den XAMLFLOW'ye işleyin" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) dosya formatı otomasyon kitaplıkları, C++ geliştiricisinin TEX'yi iki basit adımda XAMLFLOW'ye dönüştürmesine olanak tanır. İlk olarak, TEX dosya biçimini DOC'ye dönüştürmek için [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API'sini kullanabilirsiniz. İkinci olarak, gelişmiş Word Document Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak DOC'yi XAMLFLOW'ye aktarabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX'yi XAMLFLOW'ye Oluşturmak için C++ API'si" %}}
1. [Belge](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak TEX dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) üye işlevini kullanarak TEX'yi DOC'ye dönüştürün
3. Aspose.Words API'sinin [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak DOC dosyasını yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) üye işlevini kullanarak belgeyi XAMLFLOW biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
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

{{% blocks/products/pf/feature-page-section  h2="TEX Belgesinin Şifresini C++ ile Değiştirin" %}}
TEX'yi XAMLFLOW'ye oluşturma sürecinde, parola korumalı bir TEX açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir TEX dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
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

{{% blocks/products/pf/feature-page-section  h2="XAMLFLOW Dosya Düzenlemesini C++ ile Kısıtla" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak XAMLFLOW dosya düzenlemesini de kısıtlayabilirsiniz. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli eylemlere izin vermeniz gerekebilir. API, [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod örneği, yalnızca form alanlarında düzenleme yapılabilmesi için bir belgede düzenlemenin nasıl kısıtlanacağını gösterir.
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
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-pcl/" name="TEX İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-odt/" name="TEX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-dotm/" name="TEX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-mhtml/" name="TEX İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-dot/" name="TEX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-ps/" name="TEX İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-flatopc/" name="TEX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-markdown/" name="TEX İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-ott/" name="TEX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-wordml/" name="TEX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-dotx/" name="TEX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/tex-to-rtf/" name="TEX İle RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}