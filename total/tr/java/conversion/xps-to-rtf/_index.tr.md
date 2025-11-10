---
title: Çevrimiçi XPS'yi RTF'ye Dönüştürme veya XPS Dosyalarını Dönüştürmek için Java tabanlı Uygulama Geliştirme
description: XPS dosyalarını RTF dosyalarına dönüştürmek için ücretsiz çevrimiçi uygulama. XPS belgeleri için Java dönüştürme kitaplığı kodu. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: RTF
otherformats: PS ODT DOTX MARKDOWN DOTM XAMLFLOW RTF PCL OTT WORDML DOT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Çevrimiçi XPS'den RTF'ye Dönüştürme Uygulaması ve XPS Dosyalarını Dönüştürmek İçin Java Kodu" h2="Güçlü Java tabanlı XPS dönüştürme ve dışa aktarma uygulaması geliştirin. Java otomasyon API'si aracılığıyla tek veya birden fazla XPS dosyasını RTF ve diğer formatlara dönüştürün. XPS dosyalarını anında indirerek uygulama aracılığıyla çevrimiçi olarak ücretsiz dönüştürün." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Ücretsiz Çevrimiçi XPS - RTF Dönüştürme Uygulaması" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=rtf&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Dosyalarını Uygulamayı Kullanarak Çevrimiçi Olarak RTF Dosyalarına Dönüştürün" %}}

1. Dönüştürülecek XPS dosyalarını yükleyin
1. XPS boyutuna bağlı olarak birkaç saniye veya daha fazla bekleyin
1. Yükleme durum çubuğunu takip edin
1. "Dönüştür" butonuna tıklayın
1. XPS RTF belgesine dönüştürülecek
1. Dönüştürülen RTF dosyasını indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="XPS'yi Java Otomasyon API'si aracılığıyla RTF'ye dönüştürün" %}}


1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak XPS dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) kullanarak XPS'yi DOC'ye dönüştürün yöntem
3. DOC dosyasını Aspose.Words'ün [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak RTF biçiminde kaydedin ve RTF'yi ayarlayın SaveFormat olarak



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

XPS dosyasını RTF dosyasına Dönüşüm Gereksinimleri, Java ile Şifre Korumalı XPS Belgesini Açın gibi diğer özelliklerle kaydetmek için birkaç örnek daha.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Java kullanarak XPS Dosya Dönüştürme Uygulamasını Geliştirin</h2>

XPS dosyalarını RTF belgesine kolayca kaydetmek ve dışa aktarmak için Java tabanlı bir yazılım uygulaması geliştirmeye mi ihtiyacınız var? [Aspose.Total for Java](https://products.aspose.com/total/tr/java/) ile herhangi bir Java geliştiricisi, Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, E-posta dosyaları, Görüntüler (JPG, PNG, BMP, GIF) ve diğer formatlar dahil olmak üzere çeşitli formatlarda dönüştürme uygulamasını programlamak için yukarıdaki API kodunu entegre edebilir. Belge dönüştürme için güçlü Java kütüphanesi, XPS formatı da dahil olmak üzere birçok popüler formatı destekler. Programcılar, belgeleri diğer formatlara aktarırken ve işlerken, [Aspose.Words for Java](https://products.aspose.com/words/tr/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/tr/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/tr/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/tr/java/) ve daha fazlası dahil olmak üzere Aspose.Total for Java alt API'lerini kullanabilirler.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Java için Dönüştürme Kütüphanesi" %}}

Aspose.Total for Java'i sisteminize entegre etmek için alternatif seçenekler mevcuttur. Lütfen ihtiyaçlarınıza uygun olanı seçin ve adım adım talimatları izleyin:<br /><br />

- Aspose.Total for Java'i doğrudan Maven tabanlı bir projeden kullanın ve pom.xml'e ilgili alt API'yi ekleyin.
- Alternatif olarak [indirmeler](https://releases.aspose.com/total/java)'den bir ZIP dosyası da alınabilir.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="XPS'yi RTF'ye Kaydetme Uygulama Gereksinimleri" %}}

Java Runtime Environment (JRE) çalıştırabilen herhangi bir işletim sistemi Aspose.Total for Java'i çalıştırabilir. Aşağıda çoğunlukla desteklenen işletim sistemleri listelenmiştir, ancak hepsi değil. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS ve diğerleri
- macOS : 10.9 (Mavericks) ve üzeri
- Mobil : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



XPS'i **RTF (Zengin Metin Biçimi)**'e dönüştürmek, temel biçimlendirmeyi korurken çoğu kelime işlemcisiyle maksimum uyumluluk sağlar ve farklı yazılım ortamlarında belge paylaşımı için ideal hale getirir.



{{% blocks/products/pf/agp/feature-section-col title="Ana Kullanım Alanları" %}}



* Kolay dağıtım için basit rapor dönüşümü.

* Evrensel format desteği gerektiren yasal yazışmalar.

* Birden fazla platformla uyumlu eğitim görevleri.

* Geniş çapta okunabilir formatta eski belgelerin arşivlenmesi.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Otomasyon Senaryoları" %}}



* XPS dosyalarının RTF'ye evrensel erişim için toplu dönüşümü.

* Otomatik içerik yönetim sistemleriyle entegrasyon.

* Karışık platformlu kurumsal ortamlarda kolay paylaşım.

* Eski belge göçü için dönüşüm boruları.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}