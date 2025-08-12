---
title: CGM'yi PS'ye Dışa Aktarmak için Java API
description: Yerinde Java API kullanarak CGM'yi PS'ye dönüştürün
url_ignore: /tr/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java aracılığıyla CGM'yi PS'ye dönüştürün" h2="Herhangi bir üçüncü taraf uygulaması kullanmadan CGM'yi PS'ye Oluşturmak için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
İki basit adımı kullanarak CGM'yi PS'ye dönüştürebilirsiniz. Öncelikle [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak CGM dosyasını DOC'a dönüştürmeniz gerekir. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi PS'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for Java](https://products.aspose.com/total/java/) paketi kapsamında gelir.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi PS'ye Dönüştürmek için Java API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak CGM dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak CGM'yi DOC'ye dönüştürün yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak PS biçiminde kaydedin ve PS'yi ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
CGM'yi PS'ye dönüştürürken belgeniz parola korumalı olsa bile PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) kullanarak belgeyi açabilirsiniz. Şifrelenmiş dosyayı açmak için bir [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) nesnesi oluşturmanız ve CGM'yi sahibinin parolasını kullanarak açmanız gerekir.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifre Korumalı CGM Belgesini Açın" %}}
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
{{% blocks/products/pf/feature-page-summary %}}
```
CGM (Bilgisayar Grafikleri Meta Dosyası) dosyalarını PS (PostScript) formatına dönüştürmek, hassas, yüksek kaliteli baskı ve profesyonel yayıncılık sonuçları elde etmede kritik bir adımdır. PostScript'in cihazdan bağımsız formatı, karmaşık vektör grafiklerin, mühendislik diyagramlarının ve teknik illüstrasyonların baskı makinelerine veya yayıncılık sistemlerine aktarıldığında doğruluğunu ve sadakatini korumasını sağlar. Bu, tutarlı, ölçeklenebilir ve baskıya hazır çıktılar gerektiren endüstriler için CGM'den PS'ye dönüşümün vazgeçilmez olduğunu gösterir.

## ✅ Ana Kullanım Alanları
- **Endüstriyel Kalitede Vektör Baskı** – Üretim, mühendislik ve mimari belgeler için keskin, ölçeklenebilir teknik diyagramlar oluşturun.
- **Teknik İllüstrasyonların PostScript Tabanlı Sistemlerde Arşivlenmesi** – Vektör varlıkları uzun vadeli erişilebilirlik ve baskı uyumluluğu için optimize edilmiş bir formatta saklayın.
- **CGM Diyagramlarının Yayınlama İşlemi İçin Hazırlanması** – Profesyonel sayfa düzeni ve dizgi iş akışlarına sorunsuz entegrasyonu sağlayın.
- **Fiziksel Belge Üretimi** – Kılavuzlar, kataloglar ve büyük formatlı teknik grafikler için baskıya hazır dosyalar oluşturun.

## ⚙️ Otomasyon Senaryoları
- **Java Tabanlı Baskı Akışı Oluşturucuları** – Kurumsal baskı iş akışları için CGM dosyalarını programlı olarak yüksek çözünürlüklü PS çıktısına dönüştürün.
- **Vektörden PostScript'e Toplu Dönüştürücüler** – Geniş grafik arşivlerini verimli bir şekilde yönetmek için büyük ölçekli dönüşüm süreçlerini otomatikleştirin.
- **Yayıncılık Boru Hattı Entegrasyonu** – Otomatik belge oluşturma ve profesyonel yayıncılık sistemlerine CGM'den PS'ye dönüşümü gömerek tutarlı, yüksek kaliteli sonuçlar elde edin.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}