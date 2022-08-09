---
title: TEX'yi MHTML'ye Oluşturmak için Android API
description: Java API aracılığıyla Android üzerinden TEX'yi MHTML'ye dönüştürün
url: /tr/android-java/conversion/tex-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: MHTML
otherformats: WORDML FLATOPC OTT PCL ODT XAMLFLOW PS DOCM DOTM MARKDOWN DOT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Android'de TEX'yi MHTML'ye işleyin" h2="Herhangi bir yazılım yüklemeden mobil uygulamalarda TEX'yi MHTML'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) paketinin iki API'sini kullanarak TEX'den MHTML'ye dönüştürme özelliğini mobil uygulamalarınıza entegre edebilirsiniz. Öncelikle [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) kullanarak TEX dosyasını DOC'ye dönüştürmeniz gerekir. İkinci olarak, Kelime İşlem API'sini [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) kullanarak DOC'yi MHTML'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla Android'de TEX'yi MHTML'ye dönüştürün" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak TEX dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak TEX'yi DOC'ye dönüştürün ) yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak MHTML formatına kaydedin ve MHTML'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) ve [Java üzerinden Aspose.Words for Android](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de TEX Dosya Bilgilerini Alın" %}}
TEX'yi MHTML'ye dönüştürmeden önce, yazar, oluşturulma tarihi, anahtar sözcükler, değiştirme tarihi, konu ve başlık gibi belge hakkında bilgilere ihtiyacınız olabilir. Bu bilgi, dönüştürme işlemi için karar vermede yardımcı olur. Güçlü [Java üzerinden Android için Aspose.PDF](https://docs.aspose.com/pdf/androidjava/) API'sini kullanarak hepsini elde edebilirsiniz. Bir TEX dosyası hakkında dosyaya özel bilgi almak için önce [getInfo](https://) kullanarak [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) nesnesini alın referans.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) yöntemi. DocumentInfo nesnesi alındığında, tek tek özelliklerin değerlerini alabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX document
Document doc = new Document("template.tex");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de MHTML Belgesine Son Notlar Ekleme" %}}
Belge dönüştürmenin yanı sıra, [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API'sini kullanarak Android Uygulamalarınıza bir dizi başka özellik de ekleyebilirsiniz. Bu özelliklerden biri de MHTML belgesine son not ekleme ve numaralandırmadır. Bir MHTML belgesine dipnot veya son not eklemek istiyorsanız, lütfen DocumentBuilder.InsertFootnote yöntemini kullanın. Bu yöntem, belgeye bir dipnot veya son not ekler. EndnoteOptions ve FootnoteOptions sınıfları, dipnot ve son not için numaralandırma seçeneklerini temsil eder.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.mhtml", SaveFormat.MHTML);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-wordml/" name="TEX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-flatopc/" name="TEX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-ott/" name="TEX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-pcl/" name="TEX İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-odt/" name="TEX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-xamlflow/" name="TEX İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-ps/" name="TEX İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-mhtml/" name="TEX İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-dotm/" name="TEX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-markdown/" name="TEX İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-dot/" name="TEX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/tex-to-dotx/" name="TEX İle DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}