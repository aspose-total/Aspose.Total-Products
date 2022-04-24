---
title: Java ile JSON Formatını RTF'ye Dönüştür
description: Microsoft Word kullanmadan Java'da JSON'u RTF'ye ayrıştırın
url: /tr/java/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: EPUB FLATOPC PCL WORDML DOTX PS DOCM RTF DOC WORD MOBI ODT DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile JSON Formatını RTF'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> Word kullanmadan JSON'u RTF'ye ayrıştırmak için şirket içi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak Java uygulamalarınızda JSON'u iki aşamalı bir süreçte RTF'ye dönüştürebilirsiniz. İlk olarak, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak JSON'u PDF'ye ayrıştırabilirsiniz. İkinci adımda, Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak PDF'yi RTF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile JSON Formatını RTF'ye Dönüştür" %}}
1. Yeni bir [Çalışma Kitabı](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) sınıfını ve [Kaydet](https://apireference.aspose.com/) kullanarak JSON dosyasını çalışma sayfasına aktarın cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF olarak
3. [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak PDF belgesi yükleyin
4. [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak belgeyi RTF biçiminde kaydedin )) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
Ayrıca API, [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) kullanarak JSON'u RTF'ye ayrıştırırken JSON'unuz için düzen seçeneklerini ayarlamanıza olanak tanır. Diziyi bir tablo olarak işlemenize, boş değerleri yoksaymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Tüm bu seçenekler, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını Java ile RTF'ye Dönüştür" %}}
API'yi kullanarak ayrıca JSON'u filigranla RTF'ye ayrıştırabilirsiniz. RTF belgenize filigran eklemek için önce JSON dosyasını PDF'ye dönüştürebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan PDF dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin. Filigranı ekledikten sonra belgeyi RTF'ye kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-flatopc/" name="JSON İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-docm/" name="JSON İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-word/" name="JSON İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-wordml/" name="JSON İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-odt/" name="JSON İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-rtf/" name="JSON İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-doc/" name="JSON İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-mobi/" name="JSON İle MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-ott/" name="JSON İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-dotx/" name="JSON İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-pcl/" name="JSON İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-dot/" name="JSON İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-epub/" name="JSON İle EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/json-to-ps/" name="JSON İle PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}