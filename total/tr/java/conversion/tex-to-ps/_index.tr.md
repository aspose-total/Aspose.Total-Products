---
title: TEX'yi PS'ye Dışa Aktarmak için Java API
description: Yerinde Java API kullanarak TEX'yi PS'ye dönüştürün
url: /tr/java/conversion/tex-to-ps/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PS
otherformats: RTF ODT DOTX MHTML FLATOPC PCL DOT OTT DOTM XAMLFLOW WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla TEX'yi PS'ye dönüştürün" h2="Herhangi bir üçüncü taraf uygulaması kullanmadan TEX'yi PS'ye Oluşturmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak TEX'yi PS'ye dönüştürebilirsiniz. Öncelikle [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak TEX dosyasını DOC'a dönüştürmeniz gerekir. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi PS'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX'yi PS'ye Dönüştürmek için Java API" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak TEX dosyasını açın
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak TEX'yi DOC'ye dönüştürün ) yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak PS biçiminde kaydedin ve PS'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Words for Java](https://docs.aspose.com/words/java/) içerir kurulum/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
TEX'yi PS'ye dönüştürürken belgeniz parola korumalı olsa bile PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) kullanarak belgeyi açabilirsiniz. Şifrelenmiş dosyayı açmak için bir [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturmanız ve TEX'yi sahibinin parolasını kullanarak açmanız gerekir.  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifre Korumalı TEX Belgesini Açın" %}}
Giriş belgenizi PS dosya formatına kaydederken, belgenizi dosya sistemi yerine veritabanına da kaydedebilirsiniz. Belge nesnelerini bir veritabanına depolamak ve veritabanından almak için uygulamanız gerekebilir. Herhangi bir içerik yönetim sistemi uyguluyorsanız bu gerekli olacaktır. PS'nizi veritabanına kaydetmek için genellikle bir bayt dizisi elde etmek için belgeyi seri hale getirmek gerekir. Bu, [Aspose.Words for Java](https://products.aspose.com/words/Java/) API kullanılarak yapılabilir. Bayt dizinizi aldıktan sonra SQL deyimini kullanarak veritabanında saklayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-rtf/" name="TEX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-wordml/" name="TEX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-odt/" name="TEX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-flatopc/" name="TEX İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ps/" name="TEX İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-pcl/" name="TEX İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-mhtml/" name="TEX İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dotm/" name="TEX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ott/" name="TEX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dotx/" name="TEX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-xamlflow/" name="TEX İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-markdown/" name="TEX İle MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}