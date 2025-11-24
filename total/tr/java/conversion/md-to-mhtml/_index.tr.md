---
title: MD'yi MHTML'ye Dışa Aktarmak için Java API
description: Yerinde Java API kullanarak MD'yi MHTML'ye dönüştürün
url_ignore: /tr/java/conversion/md-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: MHTML
otherformats: RTF XAMLFLOW MHTML ODT PCL DOTM DOT WORDML PS DOTX FLATOPC MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla MD'yi MHTML'ye dönüştürün" h2="Herhangi bir üçüncü taraf uygulaması kullanmadan MD'yi MHTML'ye Oluşturmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak MD'yi MHTML'ye dönüştürebilirsiniz. Öncelikle [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak MD dosyasını DOC'a dönüştürmeniz gerekir. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi MHTML'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi MHTML'ye Dönüştürmek için Java API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MD dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak MD'yi DOC'ye dönüştürün yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak MHTML biçiminde kaydedin ve MHTML'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
MD'yi MHTML'ye dönüştürürken belgeniz parola korumalı olsa bile PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) kullanarak belgeyi açabilirsiniz. Şifrelenmiş dosyayı açmak için bir [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturmanız ve MD'yi sahibinin parolasını kullanarak açmanız gerekir.  
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
Giriş belgenizi MHTML dosya formatına kaydederken, belgenizi dosya sistemi yerine veritabanına da kaydedebilirsiniz. Belge nesnelerini bir veritabanına depolamak ve veritabanından almak için uygulamanız gerekebilir. Herhangi bir içerik yönetim sistemi uyguluyorsanız bu gerekli olacaktır. MHTML'nizi veritabanına kaydetmek için genellikle bir bayt dizisi elde etmek için belgeyi seri hale getirmek gerekir. Bu, [Aspose.Words for Java](https://products.aspose.com/words/Java/) API kullanılarak yapılabilir. Bayt dizinizi aldıktan sonra SQL deyimini kullanarak veritabanında saklayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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



Markdown (MD) dosyalarını MHTML (Web Arşivi) formatına dönüştürmek, biçimlendirme, resimler ve bağlantılar dahil olmak üzere tüm belgenin tek bir web'e hazır dosyada paketlenmesine olanak tanır. MHTML dosyaları, Markdown içeriğini tarayıcılar arasında paylaşmak, belgeleri arşivlemek ve taşınabilir web sayfalarını dağıtmak için idealdir.



{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}



* Markdown belgelerini kendi içinde barındıran web sayfaları olarak arşivleme.

* Herhangi bir tarayıcıda çevrimdışı okuma için taşınabilir raporlar oluşturma.

* Kullanıcı kılavuzlarını veya teknik rehberleri tek dosya web arşivleri olarak dağıtma.

* Gömülü medya içeren Markdown tabanlı proje belgelerini koruma.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}



* Markdown depolarının geceleyin MHTML'ye otomatik dönüştürülmesi ve web dağıtımı.

* Dahili bilgi tabanı belgelerinin MHTML formatında toplu arşivlenmesi.

* İçerik yönetimi borularıyla Markdown'tan MHTML dosyaları oluşturma entegrasyonu.

* Tarayıcıya hazır belgeler oluşturmak için CI/CD iş akışlarında tetiklenen dönüşüm.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}