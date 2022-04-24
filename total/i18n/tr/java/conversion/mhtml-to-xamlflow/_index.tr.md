---
title: MHTML'yi XAMLFLOW'ye Dışa Aktarmak için Java API
description: Yerinde Java API kullanarak MHTML'yi XAMLFLOW'ye dönüştürün
url: /tr/java/conversion/mhtml-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: XAML_FLOW
otherformats: RTF XAMLFLOW PS OTT ODT MARKDOWN DOTX DOTM FLATOPC WORDML DOT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla MHTML'yi XAMLFLOW'ye dönüştürün" h2="Herhangi bir üçüncü taraf uygulaması kullanmadan MHTML'yi XAMLFLOW'ye Oluşturmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak MHTML'yi XAMLFLOW'ye dönüştürebilirsiniz. Öncelikle [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak MHTML dosyasını DOC'a dönüştürmeniz gerekir. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi XAMLFLOW'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML'yi XAMLFLOW'ye Dönüştürmek için Java API" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MHTML dosyasını açın
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak MHTML'yi DOC'ye dönüştürün ) yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak XAMLFLOW biçiminde kaydedin ve XAMLFLOW'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Words for Java](https://docs.aspose.com/words/java/) içerir kurulum/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
MHTML'yi XAMLFLOW'ye dönüştürürken belgeniz parola korumalı olsa bile PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) kullanarak belgeyi açabilirsiniz. Şifrelenmiş dosyayı açmak için bir [Belge](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturmanız ve MHTML'yi sahibinin parolasını kullanarak açmanız gerekir.  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifre Korumalı MHTML Belgesini Açın" %}}
Giriş belgenizi XAMLFLOW dosya formatına kaydederken, belgenizi dosya sistemi yerine veritabanına da kaydedebilirsiniz. Belge nesnelerini bir veritabanına depolamak ve veritabanından almak için uygulamanız gerekebilir. Herhangi bir içerik yönetim sistemi uyguluyorsanız bu gerekli olacaktır. XAMLFLOW'nizi veritabanına kaydetmek için genellikle bir bayt dizisi elde etmek için belgeyi seri hale getirmek gerekir. Bu, [Aspose.Words for Java](https://products.aspose.com/words/Java/) API kullanılarak yapılabilir. Bayt dizinizi aldıktan sonra SQL deyimini kullanarak veritabanında saklayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-rtf/" name="MHTML İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-wordml/" name="MHTML İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-odt/" name="MHTML İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-flatopc/" name="MHTML İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-ps/" name="MHTML İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-pcl/" name="MHTML İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-mhtml/" name="MHTML İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-dotm/" name="MHTML İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-ott/" name="MHTML İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-dotx/" name="MHTML İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-xamlflow/" name="MHTML İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/mhtml-to-markdown/" name="MHTML İle MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}