---
title: MD'yi PCL'ye Dışa Aktarmak için Java API
description: Yerinde Java API kullanarak MD'yi PCL'ye dönüştürün
url_ignore: /tr/java/conversion/md-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PCL
otherformats: PCL ODT OTT MHTML DOTM MARKDOWN RTF FLATOPC WORDML DOT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla MD'yi PCL'ye dönüştürün" h2="Herhangi bir üçüncü taraf uygulaması kullanmadan MD'yi PCL'ye Oluşturmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak MD'yi PCL'ye dönüştürebilirsiniz. Öncelikle [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak MD dosyasını DOC'a dönüştürmeniz gerekir. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi PCL'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi PCL'ye Dönüştürmek için Java API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MD dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak MD'yi DOC'ye dönüştürün yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak PCL biçiminde kaydedin ve PCL'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
MD'yi PCL'ye dönüştürürken belgeniz parola korumalı olsa bile PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) kullanarak belgeyi açabilirsiniz. Şifrelenmiş dosyayı açmak için bir [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturmanız ve MD'yi sahibinin parolasını kullanarak açmanız gerekir.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifre Korumalı MD Belgesini Açın" %}}
Giriş belgenizi PCL dosya formatına kaydederken, belgenizi dosya sistemi yerine veritabanına da kaydedebilirsiniz. Belge nesnelerini bir veritabanına depolamak ve veritabanından almak için uygulamanız gerekebilir. Herhangi bir içerik yönetim sistemi uyguluyorsanız bu gerekli olacaktır. PCL'nizi veritabanına kaydetmek için genellikle bir bayt dizisi elde etmek için belgeyi seri hale getirmek gerekir. Bu, [Aspose.Words for Java](https://products.aspose.com/words/Java/) API kullanılarak yapılabilir. Bayt dizinizi aldıktan sonra SQL deyimini kullanarak veritabanında saklayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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
```
{{< blocks/products/pf/agp/feature-section >}}



Markdown (MD) dosyalarını PCL (Yazıcı Komut Dili)’ye dönüştürmek, lazer ve mürekkep püskürtmeli yazıcılarla uyumlu, yazdırmaya hazır dosyalar oluşturur. PCL dönüşümü, teknik belgeler, raporlar ve iş akışı otomasyonu üretmek için uygun bir seçenektir, kurumsal baskı ortamlarında.



{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}



* PCL destekleyen yazıcılarda Markdown tabanlı raporların yazdırılması.

* Toplu belge dağıtımı için PCL çıktısı oluşturma.

* Markdown belgelerini yazdırmaya hazır formatlara dönüştürme.

* Ofis veya üretim baskı iş akışları için teknik talimatların hazırlanması.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}



* Kurumsal baskı için Markdown dosyalarının zamanlanmış toplu dönüşümü.

* Yazdırma sunucularıyla entegrasyon, Markdown belgelerinden PCL otomatik oluşturma.

* Markdown’i PCL’ye dönüştüren otomatik yazdırma boruları.

* Yüksek hacimli PCL yazıcılar için tetikleyici tabanlı belge üretimi.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}